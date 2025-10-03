<template>
    <footer class="w-full grid-container pb-10 lg:pb-20 mt-auto">
        <div class="w-full flex flex-col gap-10 md:gap-20 lg:gap-9">
            <div class="w-full text-white flex max-lg:flex-col gap-6 md:gap-0 lg:gap-6 xl:gap-20 py-8 md:pt-10 md:pb-[30px] lg:py-12 px-5 md:px-14 lg:px-4 xl:px-[65px] rounded-[37px] md:rounded-[50px] bg-gradient-to-b from-[#136BFB] to-[#6E99E1]">
                <div class="flex lg:flex-col md:gap-[90px] lg:gap-8 w-full lg:w-1/2">
                    <div class="flex flex-col gap-2 md:gap-1.5 lg:gap-3">
                        <p class="text-[23px] md:text-[35px] font-medium leading-[100%]">Свяжитесь с нами</p>
                        <p class="text-[12px] md:text-[15px] leading-[18.7px] md:leading-[24px] md:max-w-[345px] lg:w-auto">
                            Оставьте заявку или свяжитесь с нами удобным способом
                        </p>
                    </div>
                    <div class="relative md:min-w-[309px] md:min-h-[150px] lg:min-h-auto lg:wmin--auto max-lg:overflow-hidden max-md:hidden">
                        <img src="/images/footer/forms.png" alt="" class="md:absolute left-5 lg:left-0 lg:static md:min-w-[377px] lg:w-full">
                    </div>
                </div>
                <div class="flex flex-col gap-10 md:gap-12 xl:gap-20 w-full lg:w-1/2">
                    <div class="flex flex-col gap-3 md:gap-3.5 xl:gap-7">
                        <p class="text-[23px] md:text-[25px] leading-[100%] font-medium xl:font-semibold">Отправить заявку</p>
                        <form class="flex max-sm:flex-col gap-1.5 md:gap-3 w-full">
                            <input type="text" placeholder="Ваш e-mail" class="rounded-full grow flex items-center h-10 px-[18px] md:px-7 xl:px-8 bg-white/40 text-white placeholder:text-white font-medium text-[12px] md:text-[15px] leading-[100%]">
                            <button class="rounded-full flex items-center h-10 justify-center bg-white text-[#136BFB] font-semibold text-[13px] md:text-[16px] leading-[100%] w-full sm:w-[170px]">Отправить</button>
                        </form>
                    </div>
                    <div class="flex max-sm:flex-col gap-6 justify-between">
                        <div class="flex max-md:flex-col gap-4 md:justify-between">
                            <a href="https://t.me/rsnbim_support" target="_blank" class="flex items-center gap-3 md:gap-5 xl:gap-4">
                                <img src="/images/footer/tg2.svg" alt="">
                                <span>@rsnbim_support</span>
                            </a>
                            <a href="mailto:info@rsnbim.ru" target="_blank" class="flex items-center gap-3 md:gap-5 xl:gap-4">
                                <img src="/images/footer/mail.svg" alt="">
                                <span>info@rsnbim.ru</span>
                            </a>
                        </div>
                        <img src="/images/footer/forms.png" alt="" class="w-full sm:w-1/2 md:hidden">
                    </div>
                </div>
            </div>
            <div class="flex max-sm:flex-col gap-2 sm:gap-10 justify-between">
                <div class="flex flex-col gap-3">
                    <a href="/">
                        <img src="/images/header/logo.png" alt="" class="w-[109px] sm:w-[158px]">
                    </a>
                    <p class="max-sm:hidden text-[#ADADAD] w-full sm:max-w-[330px] md:max-w-[420px] lg:max-w-[510px] text-[8px] sm:text-[11px] leading-[13px] sm:leading-[21px]">
                        Мы используем cookies для сбора анонимных данных о пользователях.  Эти данные помогают настраивать рекламу  и анализировать трафик. Продолжая использовать наш сайт, вы соглашаетесь на сбор и обработку таких данных.
                    </p>
                </div>
                <div class="flex max-sm:flex-col gap-2 sm:gap-6 lg:gap-[105px]">
                    <div class="grid grid-cols-2 sm:grid-cols-1 w-fit max-sm:gap-x-5 gap-y-4 text-[12px] sm:text-[15px] leading-[100%]">
                        <a href="/" class="min-w-[136px]">Как пользоваться</a>
                        <a href="/" class="min-w-[136px]">Тарифы</a>
                        <a href="/" class="min-w-[136px]">Помощь</a>
                        <a href="/" class="min-w-[136px]">Договор-оферта</a>
                    </div>
                    <div class="flex sm:flex-col max-sm:items-center gap-9 sm:gap-4">
                        <button class="w-fit px-4 py-1.5 rounded-full border border-[#136BFB] text-[#136BFB] font-semibold text-[12px] sm:text-[16px] leading-[100%]">Попробовать</button>
                        <div class="flex items-center gap-2">
                            <a href="/">
                                <img src="/images/footer/vk.svg" alt="" class="w-7 sm:w-9">
                            </a>
                            <a href="/">
                                <img src="/images/footer/tg.svg" alt="" class="w-7 sm:w-9">
                            </a>
                        </div>
                    </div>
                    <p class="mt-0.5 sm:hidden text-[#ADADAD] w-full sm:max-w-[330px] md:max-w-[420px] lg:max-w-[510px] text-[8px] sm:text-[11px] leading-[13px] sm:leading-[21px]">
                        Мы используем cookies для сбора анонимных данных о пользователях.  Эти данные помогают настраивать рекламу  и анализировать трафик. Продолжая использовать наш сайт, вы соглашаетесь на сбор и обработку таких данных.
                    </p>
                </div>
            </div>
        </div>
    </footer>
</template>

<script setup>

</script>