<template>
    <div class="flex max-sm:flex-col md:items-center xl:items-start gap-6 md:gap-4 md:justify-between">
        <div class="flex flex-col gap-2.5 md:gap-3.5 xl:gap-11">
            <a href="/plugins" class="flex items-center gap-2.5">
                <img src="/images/plugins/arrow.svg" alt="" class="w-1.5 md:w-2">
                <span class="text-[#ADADAD] text-[13px] md:text-[15px] leading-[100%]">Плагины</span>
            </a>
            <div class="flex flex-col">
                <p class="text-[25px] md:text-[38px] xl:text-[40px] leading-[130%] font-medium w-full md:max-w-[443px] xl:max-w-[536px]">Плагин отслеживания изменений в модели</p>
                <p class="max-xl:hidden text-[15px] leading-[25px]">Контроль за изменениями модели в несколько кликов</p>
            </div>
        </div>
        <img src="/images/plugins/3.png" alt="" class="w-[83%] sm:w-1/2 md:w-[366px] xl:w-[463px] max-sm:mx-auto">
    </div>
    <div class="flex flex-col gap-9 md:gap-14 items-center">
        <div class="flex flex-col gap-6 md:gap-7">
            <div class="flex gap-1.5 md:gap-4 items-start">
                <img src="/images/plugins/check.svg" alt="w-5 md:w-7 rounded-full overflow-hidden">
                <div class="flex flex-col gap-1">
                    <p class="text-[16px] md:text-[21px] leading-[100%] font-semibold max-w-[740px]">Позволяет определить, кто и когда редактировал элементы в Revit-модели, </p>
                    <p class="text-[12px] md:text-[15px] leading-[160%] flex flex-col gap-3 max-w-[785px] xl:max-w-[832px]">
                        <span>а также получить наглядную статистику активности пользователей.</span>
                        <span>Этот функционал особенно полезен для BIM-менеджеров и руководителей команд при контроле над качеством проектирования и соблюдением стандартов.</span>
                    </p>
                </div>
            </div>
            <img src="/images/plugins/scheme1.png" alt="" class="w-full max-w-[713px] mx-auto">
        </div>
        <div class="flex flex-col gap-6 md:gap-7">
            <div class="flex gap-1.5 md:gap-4 items-start">
                <img src="/images/plugins/check.svg" alt="w-5 md:w-7 rounded-full overflow-hidden">
                <div class="flex flex-col gap-1">
                    <p class="text-[16px] md:text-[21px] leading-[100%] font-semibold max-w-[740px]">Быстрый способ узнать, кто последний редактировал элемент модели.</p>
                    <div class="text-[12px] md:text-[15px] leading-[160%] flex flex-col gap-2 max-w-[785px] xl:max-w-[832px]">
                        <div class="flex items-start gap-2">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>После активации команды откроется окно, где можно выбрать интересующий элемент.</p>
                        </div>
                        <div class="flex items-start gap-2">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>В окне отобразится имя пользователя и время последнего изменения.</p>
                        </div>
                        <div class="flex items-start gap-2">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Если данные ещё не были загружены, плагин предложит загрузить историю за 60, 180 или 360 дней.</p>
                        </div>
                    </div>
                </div>
            </div>
            <img src="/images/plugins/scheme2.png" alt="" class="w-full max-w-[390px] mx-auto">
            <div class="text-[12px] md:text-[15px] leading-[160%] flex flex-col gap-2 max-w-[785px] xl:max-w-[832px]">
                <div class="flex items-start gap-2">
                    <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                    <p>Во время синхронизации с центральной моделью плагин фиксирует, какие элементы были изменены, кем и когда. Эти данные передаются на сервер RsnBim.</p>
                </div>
                <div class="flex items-start gap-2">
                    <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                    <p>В любой момент вы можете загрузить эту информацию обратно в модель и получить отчёты об изменениях или узнать, кто редактировал конкретный элемент.</p>
                </div>
            </div>
        </div>
        <div class="w-full max-w-[878px] p-3.5 md:py-6 md:px-10 text-white rounded-[15px] md:rounded-[30px] bg-gradient-to-b from-[#136BFB] to-[#6E99E1] flex items-start gap-1.5 md:gap-4 xl:gap-10">
            <img src="/images/plugins/alert.svg" alt="" class="w-7 md:w-12 shrink-0">
            <div class="flex flex-col gap-2 md:gap-0.5">
                <p class="text-[16px] md:text-[21px] leading-[100%] font-semibold">Команды работают только с моделями, размещёнными на серверах rsnbim.ru.</p>
                <p class="text-[12px] md:text-[15px] leading-[100%]">Сбор данных возможен только с компьютеров, на которых установлены плагины RSNBIM.</p>
            </div>
        </div> 
    </div>
</template>

<script setup>

</script>