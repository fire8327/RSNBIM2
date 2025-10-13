<template>
    <div v-if="isVisible" class="fixed z-50 bottom-4 left-1/2 -translate-x-1/2 w-[calc(100%-32px)] sm:w-auto max-w-[1100px]">
        <div class="bg-white shadow-[0px_1px_44px_-4px_#00000036] rounded-[20px] md:rounded-[30px] px-5 py-4 md:px-7 md:py-5 flex flex-col md:flex-row md:items-center gap-3 md:gap-6">
            <p class="text-[12px] md:text-[14px] leading-[18px] md:leading-[22px]">
                Мы используем файлы cookie для улучшения работы сайта. Продолжая просмотр, вы соглашаетесь с нашей политикой использования файлов cookie.
            </p>
            <div class="flex items-center gap-3 ml-auto">
                <button @click="accept" class="px-4 h-9 rounded-full bg-[#136BFB] text-white font-semibold text-[13px] md:text-[15px] leading-[100%]">
                    Ок
                </button>
            </div>
        </div>
    </div>
    
</template>

<script setup>
const isVisible = ref(false)

const STORAGE_KEY = 'rsnbim-cookie-consent'

onMounted(() => {
    try {
        const saved = localStorage.getItem(STORAGE_KEY)
        isVisible.value = saved !== 'accepted'
    } catch (e) {
        isVisible.value = true
    }
})

function accept() {
    localStorage.setItem(STORAGE_KEY, 'accepted')
    isVisible.value = false
}
</script>


