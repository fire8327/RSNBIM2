<template>
    <header class="pt-4 pb-5 w-full grid-container relative overflow-x-clip">
        <div class="flex items-center gap-2 justify-between">
            <a href="/">
                <img src="/images/header/logo.png" alt="" class="w-[109px] sm:w-[158px]">
            </a>
            <div class="flex max-xl:flex-col xl:items-center xl:gap-2 !leading-[100%] text-[14px] sm:text-[19px] xl:text-[15px] max-xl:bg-white w-[250px] sm:w-[374px] xl:w-auto max-xl:shadow-[0px_1px_44px_-4px_#00000036] max-xl:h-screen pl-10 sm:pl-[60px] xl:pl-0 pt-6 sm:pt-5 xl:pt-0 max-xl:absolute max-xl:top-0 max-xl:right-0 max-xl:z-[5] transition-all duration-500" :class="isMenuShow ? ' max-xl:translate-x-0' : 'max-xl:translate-x-[500px]'">
                <div class="flex items-center gap-14 sm:gap-[72px] xl:hidden">
                    <img src="/images/header/logo.png" alt="" class="w-[120px] sm:w-[158px]">
                    <button @click="isMenuShow = false">
                        <img src="/images/header/close.svg" alt="">
                    </button>
                </div>
                <a href="/trial" class="w-fit px-4 py-1.5 rounded-full bg-[#136BFB] text-white font-semibold mt-[52px] sm:mt-[90px] xl:mt-0">Попробовать</a>
                <div class="flex max-xl:flex-col xl:items-center w-fit gap-4 sm:gap-5 xl:gap-2 mt-7 sm:mt-10 xl:mt-0">
                    <a href="/plugins" :class="getLinkClass('/plugins')" class="main-link w-fit px-4 py-1.5 rounded-full font-medium">Плагины</a>
                    <a href="/how-use" :class="getLinkClass('/how-use')" class="main-link w-fit px-4 py-1.5 rounded-full font-medium">Как пользоваться</a>
                    <a href="/" :class="getLinkClass('/')" class="main-link w-fit px-4 py-1.5 rounded-full font-medium">Тарифы</a>
                    <a href="/" :class="getLinkClass('/help')" class="main-link w-fit px-4 py-1.5 rounded-full font-medium">Помощь</a>
                    <a href="/contacts" :class="getLinkClass('/contacts')" class="main-link w-fit px-4 py-1.5 rounded-full font-medium">Контакты</a>
                </div>
                <div class="flex flex-col gap-3 sm:gap-4 !leading-[100%] font-semibold text-[13px] sm:text-[17px] xl:text-[15px] mt-[60px] sm:pt-[54px] xl:hidden">
                    <a href="/reg" class="w-fit px-4 h-9 rounded-full flex items-center bg-[#D8E4F9] text-[#136BFB]">Регистрация</a>
                    <a href="/auth" class="w-fit px-4 h-9 rounded-full flex items-center gap-2 border border-[#136BFB] text-[#136BFB]">
                        <span>Войти</span>
                        <img src="/images/header/link-icon.svg" alt="">
                    </a>
                </div>
            </div>
            <div class="flex items-center gap-2.5 !leading-[100%] font-semibold text-[13px] sm:text-[17px] xl:text-[15px]">
                <a href="/auth" class="w-fit px-4 h-9 rounded-full flex items-center gap-2 border border-[#136BFB] text-[#136BFB] max-sm:hidden">
                    <span>Войти</span>
                    <img src="/images/header/link-icon.svg" alt="">
                </a>
                <a href="/reg" class="w-fit px-4 h-9 rounded-full flex items-center bg-[#D8E4F9] text-[#136BFB] max-sm:hidden">Регистрация</a>
                <button @click="isMenuShow = true" class="w-8 md:w-12 xl:hidden">
                    <img src="/images/header/menu.svg" alt="">
                </button>
            </div>
        </div>
    </header>
</template>

<script setup>
/* открытие меню */
const isMenuShow = ref(false)

/* получение текущего пути */
const route = useRoute()

/* функция для определения активной ссылки */
const getLinkClass = (path) => {
    const currentPath = route.path
    
    // Специальная логика для главной страницы
    if (path === '/' && currentPath === '/') {
        return 'text-[#0F0F0F] bg-[#F7F7F7]'
    }
    
    // Для остальных страниц - точное совпадение
    if (currentPath === path) {
        return 'text-[#0F0F0F] bg-[#F7F7F7]'
    }
    
    // Для вложенных страниц (например, /plugins/index)
    if (currentPath.startsWith(path) && path !== '/') {
        return 'text-[#0F0F0F] bg-[#F7F7F7]'
    }
    
    return 'bg-[#F7F7F7] text-[#ADADAD]'
}

/* закрытие мобильного меню */
const nuxtApp = useNuxtApp()
nuxtApp.hook('page:start', () => {
    isMenuShow.value = false
})
</script>