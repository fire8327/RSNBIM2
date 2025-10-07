<template>
    <div class="w-full grow col-span-full grid-container md:bg-[#F7F7F7] md:py-12 xl:py-14">
        <div class="md:bg-white md:rounded-[42px] w-full max-w-[1126px] mx-auto md:px-12 md:py-7 xl:px-[120px] xl:py-9 flex flex-col gap-6 md:gap-8 bg-wnite">
            <div class="flex flex-col gap-9 md:gap-11 xl:gap-14">
                <p class="text-[25px] md:text-[35px] xl:text-[40px] font-medium leading-[130%] md:mt-">Регистрация</p>
                <div class="flex flex-col gap-10 md:gap-6">
                    <div class="flex max-sm:flex-col gap-3 md:gap-3.5 xl:gap-4 text-[12px] md:text-[15px]">
                        <button class="w-full sm:w-1/2 h-10 md:h-14 flex items-center justify-center gap-1.5 md:gap-2 bg-[#F7F7F7] rounded-[8px] md:rounded-[11px]">
                            <img src="/images/reg/yandex.svg" alt="" class="w-[22px] md:w-7">
                            <span>Войти через Яндекс</span>
                        </button>
                        <button class="w-full sm:w-1/2 h-10 md:h-14 flex items-center justify-center gap-1.5 md:gap-2 bg-[#F7F7F7] rounded-[8px] md:rounded-[11px]">
                            <img src="/images/reg/vk.svg" alt="" class="w-[22px] md:w-7">
                            <span>Войти через VK</span>
                        </button>
                    </div>
                    <div class="flex items-center w-full gap-1.5 md:gap-2 xl:gap-4">
                        <div class="grow h-[0.5px] bg-[#ADADAD]"></div>
                        <p class="text-[12px] md:text-[15px] leading-[160%] text-[#ADADAD]">или</p>
                        <div class="grow h-[0.5px] bg-[#ADADAD]"></div>
                    </div>
                </div>
            </div>
            
        </div>
    </div>
</template>

<script setup>
/* скрытие блока в подвале */
definePageMeta({
  hideFooterContact: true
})
</script>