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
    <div class="flex flex-col gap-6 md:gap-10 xl:gap-12 col-span-full">
        <p class="text-[23px] md:text-[35px] leading-[100%] font-medium text-center">Схема работы</p>
        <div class="flex flex-col w-full">
            <div class="grid-container">
                <div class="flex items-center gap-2.5 md:gap-11 max-md:jsutify-center text-[11px] md:text-[21px] leading-[100%] font-semibold">
                    <button @click="scheme = 'Server'" class="flex items-center gap-1 md:gap-2.5 px-2.5 md:px-10 rounded-t-[12px] md:rounded-t-[21px]" :class="{'bg-[#F7F7F7]' : scheme === 'Server'}">
                        <img src="/images/scheme/server.svg" alt="" class="w-[30px] md:w-[65px]">
                        <span>Revit Server</span>
                    </button>
                    <button @click="scheme = 'Accelerator'" class="flex items-center gap-1 md:gap-2.5 px-2.5 md:px-10 rounded-t-[12px] md:rounded-t-[21px]" :class="{'bg-[#F7F7F7]' : scheme === 'Accelerator'}">
                        <img src="/images/scheme/accelerator.svg" alt="" class="w-[30px] md:w-[65px]">
                        <span>Revit Accelerator</span>
                    </button>
                </div>
            </div>
            <div class="w-full h-[194px] md:h-[490px] xl:h-[484px] relative bg-[#F7F7F7]">
                <img src="/images/scheme/server-scheme.png" alt="" class="absolute top-1/2 -translate-y-1/2 left-1/2 -translate-x-1/2 w-full max-w-[974px] transition-all duration-500" :class="scheme === 'Server' ? 'opacity-0' : 'opacity-100'">
                <img src="/images/scheme/accelerator-scheme.png" alt="" class="absolute top-1/2 -translate-y-1/2 left-1/2 -translate-x-1/2 w-full max-w-[1154px] transition-all duration-500" :class="scheme === 'Accelerator' ? 'opacity-0' : 'opacity-100'">
            </div>
        </div>
    </div>
    <div class="flex flex-col gap-9 xl:gap-10">
        <p class="text-[23px] md:text-[35px] leading-[100%] font-medium text-center max-md:-mb-4">Тарифы</p>
        <div class="flex items-center gap-2.5 md:gap-5 flex-wrap text-[10px] md:text-[13px] leading-[100%] font-medium">
            <label class="flex items-center gap-1 md:gap-2.5 py-1 px-1.5 rounded-full main-input relative">
                <input type="radio" name="city" class="sr-only" checked>
                <img src="/images/pricing/ru.svg" alt="" class="w-[18px] md:w-6">
                <span>Москва</span>
                <span class="absolute -top-2 -right-2 md:-right-3  flex items-center justify-center w-[13px] h-[13px] md:w-[22px] md:h-[22px] rounded-full bg-[#136BFB] text-white border border-white text-[8px] md:text-[14px]">3</span>
            </label>
            <label class="flex items-center gap-1 md:gap-2.5 py-1 px-1.5 rounded-full main-input relative">
                <input type="radio" name="city" class="sr-only">
                <img src="/images/pricing/ru.svg" alt="" class="w-[18px] md:w-6">
                <span>Кемерево</span>
                <span class="absolute -top-2 -right-2 md:-right-3  flex items-center justify-center w-[13px] h-[13px] md:w-[22px] md:h-[22px] rounded-full bg-[#136BFB] text-white border border-white text-[8px] md:text-[14px]">3</span>
            </label>
            <label class="flex items-center gap-1 md:gap-2.5 py-1 px-1.5 rounded-full main-input relative">
                <input type="radio" name="city" class="sr-only">
                <img src="/images/pricing/ru.svg" alt="" class="w-[18px] md:w-6">
                <span>Саратов</span>
                <span class="absolute -top-2 -right-2 md:-right-3  flex items-center justify-center w-[13px] h-[13px] md:w-[22px] md:h-[22px] rounded-full bg-[#136BFB] text-white border border-white text-[8px] md:text-[14px]">3</span>
            </label>
            <label class="flex items-center gap-1 md:gap-2.5 py-1 px-1.5 rounded-full main-input relative">
                <input type="radio" name="city" class="sr-only">
                <img src="/images/pricing/ru.svg" alt="" class="w-[18px] md:w-6">
                <span>Владивосток</span>
                <span class="absolute -top-2 -right-2 md:-right-3  flex items-center justify-center w-[13px] h-[13px] md:w-[22px] md:h-[22px] rounded-full bg-[#136BFB] text-white border border-white text-[8px] md:text-[14px]">3</span>
            </label>
            <label class="flex items-center gap-1 md:gap-2.5 py-1 px-1.5 rounded-full main-input relative">
                <input type="radio" name="city" class="sr-only">
                <img src="/images/pricing/ru.svg" alt="" class="w-[18px] md:w-6">
                <span>Санкт-Петербург</span>
                <span class="absolute -top-2 -right-2 md:-right-3  flex items-center justify-center w-[13px] h-[13px] md:w-[22px] md:h-[22px] rounded-full bg-[#136BFB] text-white border border-white text-[8px] md:text-[14px]">3</span>
            </label>
            <label class="flex items-center gap-1 md:gap-2.5 py-1 px-1.5 rounded-full main-input relative">
                <input type="radio" name="city" class="sr-only">
                <img src="/images/pricing/ru.svg" alt="" class="w-[18px] md:w-6">
                <span>Казань</span>
                <span class="absolute -top-2 -right-2 md:-right-3  flex items-center justify-center w-[13px] h-[13px] md:w-[22px] md:h-[22px] rounded-full bg-[#136BFB] text-white border border-white text-[8px] md:text-[14px]">3</span>
            </label>
            <label class="flex items-center gap-1 md:gap-2.5 py-1 px-1.5 rounded-full main-input relative">
                <input type="radio" name="city" class="sr-only">
                <img src="/images/pricing/uae.svg" alt="" class="w-[18px] md:w-6">
                <span>ОАЭ</span>
                <span class="absolute -top-2 -right-2 md:-right-3  flex items-center justify-center w-[13px] h-[13px] md:w-[22px] md:h-[22px] rounded-full bg-[#136BFB] text-white border border-white text-[8px] md:text-[14px]">3</span>
            </label>
            <label class="flex items-center gap-1 md:gap-2.5 py-1 px-1.5 rounded-full main-input relative">
                <input type="radio" name="city" class="sr-only">
                <img src="/images/pricing/pl.svg" alt="" class="w-[18px] md:w-6">
                <span>Польша</span>
                <span class="absolute -top-2 -right-2 md:-right-3  flex items-center justify-center w-[13px] h-[13px] md:w-[22px] md:h-[22px] rounded-full bg-[#136BFB] text-white border border-white text-[8px] md:text-[14px]">3</span>
            </label>
            <label class="flex items-center gap-1 md:gap-2.5 py-1 px-1.5 rounded-full main-input relative">
                <input type="radio" name="city" class="sr-only">
                <img src="/images/pricing/de.svg" alt="" class="w-[18px] md:w-6">
                <span>Германия</span>
                <span class="absolute -top-2 -right-2 md:-right-3  flex items-center justify-center w-[13px] h-[13px] md:w-[22px] md:h-[22px] rounded-full bg-[#136BFB] text-white border border-white text-[8px] md:text-[14px]">3</span>
            </label>
            <label class="flex items-center gap-1 md:gap-2.5 py-1 px-1.5 rounded-full main-input relative">
                <input type="radio" name="city" class="sr-only">
                <img src="/images/pricing/nl.svg" alt="" class="w-[18px] md:w-6">
                <span>Амстердам</span>
                <span class="absolute -top-2 -right-2 md:-right-3  flex items-center justify-center w-[13px] h-[13px] md:w-[22px] md:h-[22px] rounded-full bg-[#136BFB] text-white border border-white text-[8px] md:text-[14px]">3</span>
            </label>
            <label class="flex items-center gap-1 md:gap-2.5 py-1 px-1.5 rounded-full main-input relative">
                <input type="radio" name="city" class="sr-only">
                <img src="/images/pricing/lv.svg" alt="" class="w-[18px] md:w-6">
                <span>Латвия</span>
                <span class="absolute -top-2 -right-2 md:-right-3  flex items-center justify-center w-[13px] h-[13px] md:w-[22px] md:h-[22px] rounded-full bg-[#136BFB] text-white border border-white text-[8px] md:text-[14px]">3</span>
            </label>
        </div> 
        <div class="grid grid-cols-2 md:grid-cols-3 xl:grid-cols-5 gap-3 md:gap-5">
            <label class="cursor-pointer group py-3 px-5 md:py-2 md:px-3 rounded-[20px] flex flex-col gap-0.5 md:gap-6 main-input">
                <input type="radio" name="rate" checked class="sr-only peer">
                <div class="flex max-md:flex-col md:items-center gap-px justify-between">
                    <p class="text-xl md:text-[22px] font-semibold leading-[100%]">Start-2</p>
                    <img src="/images/pricing/1.svg" alt="" class="max-md:order-first w-8 md:w-10">
                </div>
                <div class="grid grid-cols-2 gap-x-1 gap-y-2 text-xs md:text-sm leading-[100%] w-fit text-[#ADADAD] transition-all duration-500 peer-checked:text-white">
                    <p class="font-semibold">4</p>
                    <p>CPU Core</p>
                    <p class="font-semibold">4 GB</p>
                    <p>RAM</p>
                    <p class="font-semibold">10 GB</p>
                    <p>NVME</p>
                    <p class="font-semibold">2-3</p>
                    <p>User</p>
                </div> 
                <div class="mt-2 md:mt-10 flex flex-col gap-3.5 md:gap-5 items-center text-center">
                    <p class="text-lg md:text-2xl font-semibold leading-[100%]">7 900 <span class="text-base">₽/мес</span></p>
                    <button class="text-[10px] md:text-[13px] leading-[100%] font-semibold flex items-center justify-center w-[104px] h-[32px] md:w-[133px] md:h-[41px] rounded-full border transition-all duration-500 border-[#136BFB] text-[#136BFB] group-has-[:checked]:bg-white group-has-[:checked]:border-white">Заказать</button>
                </div>
            </label>
            <label class="cursor-pointer group py-3 px-5 md:py-2 md:px-3 rounded-[20px] flex flex-col gap-0.5 md:gap-6 main-input">
                <input type="radio" name="rate" class="sr-only peer">
                <div class="flex max-md:flex-col md:items-center gap-px justify-between">
                    <p class="text-xl md:text-[22px] font-semibold leading-[100%]">Start-3</p>
                    <img src="/images/pricing/2.svg" alt="" class="max-md:order-first w-8 md:w-10">
                </div>
                <div class="grid grid-cols-2 gap-x-1 gap-y-2 text-xs md:text-sm leading-[100%] w-fit text-[#ADADAD] transition-all duration-500 peer-checked:text-white">
                    <p class="font-semibold">6</p>
                    <p>CPU Core</p>
                    <p class="font-semibold">12 GB</p>
                    <p>RAM</p>
                    <p class="font-semibold">10 GB</p>
                    <p>NVME</p>
                    <p class="font-semibold">2-3</p>
                    <p>User</p>
                </div> 
                <div class="mt-2 md:mt-10 flex flex-col gap-3.5 md:gap-5 items-center text-center">
                    <p class="text-lg md:text-2xl font-semibold leading-[100%]">9 900 <span class="text-base">₽/мес</span></p>
                    <button class="text-[10px] md:text-[13px] leading-[100%] font-semibold flex items-center justify-center w-[104px] h-[32px] md:w-[133px] md:h-[41px] rounded-full border transition-all duration-500 border-[#136BFB] text-[#136BFB] group-has-[:checked]:bg-white group-has-[:checked]:border-white">Заказать</button>
                </div>
            </label>
            <label class="cursor-pointer group py-3 px-5 md:py-2 md:px-3 rounded-[20px] flex flex-col gap-0.5 md:gap-6 main-input">
                <input type="radio" name="rate" class="sr-only peer">
                <div class="flex max-md:flex-col md:items-center gap-px justify-between">
                    <p class="text-xl md:text-[22px] font-semibold leading-[100%]">Standart-3</p>
                    <img src="/images/pricing/3.svg" alt="" class="max-md:order-first w-8 md:w-10">
                </div>
                <div class="grid grid-cols-2 gap-x-1 gap-y-2 text-xs md:text-sm leading-[100%] w-fit text-[#ADADAD] transition-all duration-500 peer-checked:text-white">
                    <p class="font-semibold">8</p>
                    <p>CPU Core</p>
                    <p class="font-semibold">16 GB</p>
                    <p>RAM</p>
                    <p class="font-semibold">30 GB</p>
                    <p>NVME</p>
                    <p class="font-semibold">3-6</p>
                    <p>User</p>
                </div> 
                <div class="mt-2 md:mt-10 flex flex-col gap-3.5 md:gap-5 items-center text-center">
                    <p class="text-lg md:text-2xl font-semibold leading-[100%]">11 900 <span class="text-base">₽/мес</span></p>
                    <button class="text-[10px] md:text-[13px] leading-[100%] font-semibold flex items-center justify-center w-[104px] h-[32px] md:w-[133px] md:h-[41px] rounded-full border transition-all duration-500 border-[#136BFB] text-[#136BFB] group-has-[:checked]:bg-white group-has-[:checked]:border-white">Заказать</button>
                </div>
            </label>
            <label class="cursor-pointer group py-3 px-5 md:py-2 md:px-3 rounded-[20px] flex flex-col gap-0.5 md:gap-6 main-input">
                <input type="radio" name="rate" class="sr-only peer">
                <div class="flex max-md:flex-col md:items-center gap-px justify-between">
                    <p class="text-xl md:text-[22px] font-semibold leading-[100%]">Pro-3</p>
                    <img src="/images/pricing/4.svg" alt="" class="max-md:order-first w-8 md:w-10">
                </div>
                <div class="grid grid-cols-2 gap-x-1 gap-y-2 text-xs md:text-sm leading-[100%] w-fit text-[#ADADAD] transition-all duration-500 peer-checked:text-white">
                    <p class="font-semibold">12</p>
                    <p>CPU Core</p>
                    <p class="font-semibold">24 GB</p>
                    <p>RAM</p>
                    <p class="font-semibold">60 GB</p>
                    <p>NVME</p>
                    <p class="font-semibold">8-12</p>
                    <p>User</p>
                </div> 
                <div class="mt-2 md:mt-10 flex flex-col gap-3.5 md:gap-5 items-center text-center">
                    <p class="text-lg md:text-2xl font-semibold leading-[100%]">13 900 <span class="text-base">₽/мес</span></p>
                    <button class="text-[10px] md:text-[13px] leading-[100%] font-semibold flex items-center justify-center w-[104px] h-[32px] md:w-[133px] md:h-[41px] rounded-full border transition-all duration-500 border-[#136BFB] text-[#136BFB] group-has-[:checked]:bg-white group-has-[:checked]:border-white">Заказать</button>
                </div>
            </label>
            <label class="cursor-pointer group py-3 px-5 md:py-2 md:px-3 rounded-[20px] flex flex-col gap-0.5 md:gap-6 main-input">
                <input type="radio" name="rate" class="sr-only peer">
                <div class="flex max-md:flex-col md:items-center gap-px justify-between">
                    <p class="text-xl md:text-[22px] font-semibold leading-[100%]">Pro-4</p>
                    <img src="/images/pricing/5.svg" alt="" class="max-md:order-first w-8 md:w-10">
                </div>
                <div class="grid grid-cols-2 gap-x-1 gap-y-2 text-xs md:text-sm leading-[100%] w-fit text-[#ADADAD] transition-all duration-500 peer-checked:text-white">
                    <p class="font-semibold">16</p>
                    <p>CPU Core</p>
                    <p class="font-semibold">32 GB</p>
                    <p>RAM</p>
                    <p class="font-semibold">60 GB</p>
                    <p>NVME</p>
                    <p class="font-semibold">8-12</p>
                    <p>User</p>
                </div> 
                <div class="mt-2 md:mt-10 flex flex-col gap-3.5 md:gap-5 items-center text-center">
                    <p class="text-lg md:text-2xl font-semibold leading-[100%]">15 900 <span class="text-base">₽/мес</span></p>
                    <button class="text-[10px] md:text-[13px] leading-[100%] font-semibold flex items-center justify-center w-[104px] h-[32px] md:w-[133px] md:h-[41px] rounded-full border transition-all duration-500 border-[#136BFB] text-[#136BFB] group-has-[:checked]:bg-white group-has-[:checked]:border-white">Заказать</button>
                </div>
            </label>
        </div>
    </div>
    <div class="flex flex-col gap-5 md:gap-gap-7 xl:gap-11">
        <p class="text-[23px] md:text-[35px] leading-[100%] font-medium text-center">Преимущества</p>
        <div class="grid grid-cols-1 sm:grid-cols-2 xl:grid-cols-3 gap-2.5 md:gap-5">
            <div class="flex flex-col gap-3.5 xl:gap-2.5 px-6 overflow-hidden relative pt-[187px] sm:pt-[334px] pb-6 md:pb-8 border-[0.55px] md:border-[0.7px] border-[#ADADAD] rounded-[23px] md:rounded-[30px]">
                <img src="/images/advantages/unification.png" alt="" class="absolute left-1/2 -translate-x-1/2 top-4 md:top-6 w-full">
                <p class="text-[16px] leading-[22px] md:text-[21px] md:leading-[100%] font-semibold">Централизованное управление проектами</p>
                <p class="text-[12px] leading-[20px] md:text-[15px] md:leading-[26px]">
                    Revit Server обеспечивает единое централизованное хранилище данных проекта, что делает совместную работу команды более организованной и эффективной.
                </p>
            </div>
            <div class="flex flex-col gap-3.5 xl:gap-2.5 px-6 overflow-hidden relative pt-[187px] sm:pt-[334px] pb-6 md:pb-8 border-[0.55px] md:border-[0.7px] border-[#ADADAD] rounded-[23px] md:rounded-[30px]">
                <img src="/images/advantages/map.png" alt="" class="absolute left-1/2 -translate-x-1/2 top-0 w-full">
                <p class="text-[16px] leading-[22px] md:text-[21px] md:leading-[100%] font-semibold">Географически распределенные команды</p>
                <p class="text-[12px] leading-[20px] md:text-[15px] md:leading-[26px]">
                    Revit Server позволяет командам, находящимся в разных географических местоположениях, работать над одним проектом, обеспечивая высокую скорость доступа к данным.
                </p>
            </div>
            <div class="flex flex-col gap-3.5 xl:gap-2.5 px-6 overflow-hidden relative pt-[187px] sm:pt-[334px] pb-6 md:pb-8 border-[0.55px] md:border-[0.7px] border-[#ADADAD] rounded-[23px] md:rounded-[30px]">
                <img src="/images/advantages/logo.png" alt="" class="absolute left-1/2 -translate-x-1/2 top-2.5 md:top-3.5 w-full">
                <p class="text-[16px] leading-[22px] md:text-[21px] md:leading-[100%] font-semibold">Интеграция с другими BIM-технологиями</p>
                <p class="text-[12px] leading-[20px] md:text-[15px] md:leading-[26px]">
                    Revit Server легко интегрируется с другими программами и приложениями BIM, что облегчает процесс совместной работы и обмена данными между различными инструментами.
                </p>
            </div>
            <div class="flex flex-col gap-3.5 xl:gap-2.5 px-6 overflow-hidden relative pt-[187px] sm:pt-[334px] pb-6 md:pb-8 border-[0.55px] md:border-[0.7px] border-[#ADADAD] rounded-[23px] md:rounded-[30px]">
                <img src="/images/advantages/protection.png" alt="" class="absolute left-1/2 -translate-x-1/2 top-1.5 md:top-7 w-full">
                <p class="text-[16px] leading-[22px] md:text-[21px] md:leading-[100%] font-semibold">Улучшенная безопасность данных</p>
                <p class="text-[12px] leading-[20px] md:text-[15px] md:leading-[26px]">
                    Revit Server обеспечивает надежную защиту данных проекта, предотвращая утерю информации и обеспечивая резервное копирование.
                </p>
            </div>
            <div class="flex flex-col gap-3.5 xl:gap-2.5 px-6 overflow-hidden relative pt-[187px] sm:pt-[334px] pb-6 md:pb-8 border-[0.55px] md:border-[0.7px] border-[#ADADAD] rounded-[23px] md:rounded-[30px]">
                <img src="/images/advantages/scheme.png" alt="" class="absolute left-1/2 -translate-x-1/2 top-0 md:top-12 w-full px-5 md:px-7">
                <p class="text-[16px] leading-[22px] md:text-[21px] md:leading-[100%] font-semibold">Многопользовательский доступ</p>
                <p class="text-[12px] leading-[20px] md:text-[15px] md:leading-[26px]">
                    Позволяет множеству участников команды одновременно работать над проектом в реальном времени, что увеличивает производительность и устраняет конфликты при одновременном редактировании данных.
                </p>
            </div>
            <div class="flex flex-col gap-3.5 xl:gap-2.5 px-6 overflow-hidden relative pt-[187px] sm:pt-[334px] pb-6 md:pb-8 border-[0.55px] md:border-[0.7px] border-[#ADADAD] rounded-[23px] md:rounded-[30px]">
                <img src="/images/advantages/load.png" alt="" class="absolute left-1/2 -translate-x-1/2 -top-2.5 md:top-3.5 w-full px-9">
                <p class="text-[16px] leading-[22px] md:text-[21px] md:leading-[100%] font-semibold">Уменьшение нагрузки на локальные серверы</p>
                <p class="text-[12px] leading-[20px] md:text-[15px] md:leading-[26px]">
                    Эффективное управление данными проекта на сервере позволяет снизить нагрузку на локальные компьютеры и серверы команды.
                </p>
            </div>
        </div>
    </div>
</template>

<script setup>
/* схема работы*/
const scheme = ref('Server')
</script>