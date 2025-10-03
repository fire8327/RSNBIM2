<template>
    <div>
        Главная страница
    </div> 
    <div class="col-span-full w-full grid-container rounded-[30px] md:rounded-[39px] bg-[#F7F7F7] py-9 xl:py-12">
        <div class="flex items-center max-xl:flex-col gap-4">
            <img src="/images/about/about.png" alt="" class="w-full xl:w-1/2 max-xl:order-last">
            <div class="flex flex-col gap-1.5 md:flex-row xl:flex-col w-full xl:w-1/2">
                <p class="text-[20px] md:text-[25px] leading-[144%] font-medium w-full md:w-[46%] xl:w-full">
                    <span class="text-[#136BFB]">Revit Server</span> — это бесплатное программное обеспечение от Autodesk Revit для организации совместной работы над проектами
                </p>
                <p class="text-[12px] md:text-[15px] leading-[180%] w-full md:w-[54%] xl:w-full">
                    Разворачиваем и администрируем Revit Server для архитектурных бюро и проектных организаций. Вам больше не нужно инвестировать в дорогостоящее оборудование, организовывать выделенный канал со статическим IP, настраивать сложную IT-инфраструктуру, VPN и межсетевые экраны. Мы быстро и безопасно развернём ваш собственный Revit Server в облаке — всего за несколько часов вы получите готовую среду для совместной работы, доступную из любой точки. 
                </p>
            </div> 
        </div>         
    </div>
    <div class="grid grid-cols-1 sm:grid-cols-2 xl:grid-cols-3 gap-3 md:gap-y-4 md:gap-x-5">
        <div class="flex flex-col w-full h-[188px] md:h-[252px] gap-3 md:gap-1.5 px-4 md:px-7 pt-5 md:pt-8 rounded-[17px] md:rounded-[22px] relative bg-[#136BFB] text-white">
            <p class="max-md:max-w-[190px] text-[16px] md:text-[21px] font-semibold leading-[100%]">Независимость от Autodesk</p>
            <p class="text-[12px] md:text-[15px] leading-[20px] md:leading-[26px]">Наши серверы не зависят от облачных сервисов Autodesk и не могут быть неожиданно заблокированы или отключены.</p>
            <img src="/images/about/lock.svg" alt="" class="absolute max-sm:top-1.5 max-sm:right-2.5 bottom-2.5 right-4 w-12 md:w-[72]">
        </div>
        <div class="flex flex-col w-full h-[188px] md:h-[252px] gap-3 md:gap-1.5 px-4 md:px-7 pt-5 md:pt-8 rounded-[17px] md:rounded-[22px] relative bg-[#F7F7F7]">
            <p class="max-md:max-w-[190px] text-[16px] md:text-[21px] font-semibold leading-[100%]">Мы берем на себя всю рутину</p>
            <p class="text-[12px] md:text-[15px] leading-[20px] md:leading-[26px]">Полностью управляем сервером, выполняем резервное копирование и регулярные обновления.</p>
            <img src="/images/about/gear.svg" alt="" class="absolute max-sm:top-2 max-sm:right-2 bottom-5 right-3 w-[54px] md:w-[85px]">
        </div>
        <div class="flex flex-col w-full h-[188px] md:h-[252px] gap-3 md:gap-1.5 px-4 md:px-7 pt-5 md:pt-8 rounded-[17px] md:rounded-[22px] relative bg-[#F7F7F7]">
            <p class="max-md:max-w-[190px] text-[16px] md:text-[21px] font-semibold leading-[100%]">Сотрудничайте эффективно</p>
            <p class="text-[12px] md:text-[15px] leading-[20px] md:leading-[26px]">Объединенные модели Revit хранятся на Вашем центральном сервере, и все участники вашей команды могут легко получить доступ к ним.</p>
            <img src="/images/about/team.svg" alt="" class="absolute max-sm:top-0.5 max-sm:right-2.5 bottom-2.5 right-3.5 w-16 md:w-102px">
        </div>
        <div class="flex flex-col w-full h-[188px] md:h-[252px] gap-3 md:gap-1.5 px-4 md:px-7 pt-5 md:pt-8 rounded-[17px] md:rounded-[22px] relative bg-[#F7F7F7]">
            <p class="max-md:max-w-[190px] text-[16px] md:text-[21px] font-semibold leading-[100%]">Экономьте время и деньги</p>
            <p class="text-[12px] md:text-[15px] leading-[20px] md:leading-[26px]">Вы не тратите огромные средства на дорогостоящий сервер и специалистов для его настройки и поддержки.</p>
            <img src="/images/about/clock.svg" alt="" class="absolute max-sm:top-3 max-sm:right-2 bottom-5 right-2 w-[58px] md:w-[97px]">
        </div>
        <div class="flex flex-col w-full h-[188px] md:h-[252px] gap-3 md:gap-1.5 px-4 md:px-7 pt-5 md:pt-8 rounded-[17px] md:rounded-[22px] relative bg-[#F7F7F7]">
            <p class="max-md:max-w-[190px] text-[16px] md:text-[21px] font-semibold leading-[100%]">Быстрый старт</p>
            <p class="text-[12px] md:text-[15px] leading-[20px] md:leading-[26px]">Закажите услугу прямо сейчас, и в течение 24 часов Вы получите доступ к вашему персональному Revit серверу. Начните работать над проектом сразу после получения доступа!</p>
            <img src="/images/about/flash.svg" alt="" class="absolute max-sm:top-1 max-sm:right-3 bottom-5 right-4 w-[46px] md:w-[75px]">
        </div>
        <div class="flex flex-col w-full h-[188px] md:h-[252px] gap-3 md:gap-1.5 px-4 md:px-7 pt-5 md:pt-8 rounded-[17px] md:rounded-[22px] relative bg-[#F7F7F7]">
            <p class="max-md:max-w-[190px] text-[16px] md:text-[21px] font-semibold leading-[100%]">Профессиональная поддержка</p>
            <p class="text-[12px] md:text-[15px] leading-[20px] md:leading-[26px]">Наша команда специалистов всегда готова ответить на ваши вопросы и помочь решить любые трудности, которые могут возникнуть в <br class="hidden sm:block md:hidden"> процессе работы.</p>
            <img src="/images/about/support.svg" alt="" class="absolute max-sm:top-2 max-sm:right-3 bottom-5 right-6 w-[54px] md:w-[68px]">
        </div>
    </div>
</template>

<script setup>

</script>