<template>
    <div @click="$emit('close')" class="fixed inset-0 bg-[#0F0F0F80] z-[9]"></div>
    <div @click.stop class="fixed top-1/2 -translate-y-1/2 left-1/2 -translate-x-1/2 w-[calc(100%-40px)] md:max-w-[825px] xl:max-w-[1118px] z-[10] rounded-[15px] md:rounded-[41px] bg-white shadow-[0px_0.78px_19.48px_3.21px_#0000002B] px-2.5 py-6 md:py-10 xl:py-14">
        <div class="relative max-h-[60vh] sm:max-h-[70vh] md:max-h-[80vh] overflow-y-auto px-2 md:px-[65px] xl:px-[105px]">
            <div class="flex flex-col gap-5 md:gap-14 xl:gap-10">
                <div class="flex items-center max-xl:flex-col gap-5 md:gap-14 xl:gap-12">
                    <div class="flex flex-col gap-5 md:gap-14 xl:gap-10 w-full">
                        <div class="flex flex-col gap-4 md:gap-7 xl:gap-5 w-full">
                            <p class="max-sm:max-w-[179px] md:max-w-[590px] w-full xl:max-w-full text-[20px] md:text-[40px] leading-[130%] font-medium">Корпоративный домен</p>
                            <div class="md:max-w-[454px] xl:max-w-[564px] max-sm:mt-10 rounded-[12px] md:rounded-[30px] flex items-center gap-1 md:gap-3 xl:gap-5 w-fit md:w-full bg-gradient-to-b from-[#136BFB] to-[#6E99E1] text-white py-1 md:py-1.5 xl:py-2.5 px-2 md:px-5 xl:px-6">
                                <img src="/images/modals/icon.png" alt="" class="w-7 md:w-[71px] xl:w-[87px]">
                                <div class="flex flex-col gap-0.5 md:gap-2">
                                    <p class="text-[14px] md:text-[21px] leading-[115%] font-semibold">Revit Server под вашим брендом</p>
                                    <p class="text-[12px] md:text-[15px] leading-[130%]">интеграция в корпоративную экосистему.</p> 
                                </div>
                            </div>
                        </div>
                        <div class="flex flex-col gap-4 md:gap-7 xl:gap-11 xl:max-w-[564px]">
                            <div class="flex flex-col gap-2 md:gap-4 xl:gap-5">
                                <div class="flex items-start gap-2 md:gap-3.5">
                                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">1</p>
                                    <div>
                                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Работайте под вашим брендом</p>
                                        <p class="text-[12px] md:text-[15px] leading-[150%]">Используйте собственный домен (например, yourcompany.ru) вместо rsnbim.ru. Это подчеркнёт профессиональный имидж компании и упростит работу сотрудников.</p>
                                    </div>
                                </div>
                                <div class="flex items-start gap-2 md:gap-3.5">
                                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">2</p>
                                    <div>
                                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Единый стиль IT-инфраструктуры</p>
                                        <p class="text-[12px] md:text-[15px] leading-[150%]">Собственный домен сохраняет единый стиль вашей IT-инфраструктуры. Используйте адреса:</p>
                                        <div class="mt-2 flex flex-col gap-1">
                                            <p class="text-[12px] md:text-[15px] leading-[150%] font-mono bg-[#F7F7F7] px-2 py-1 rounded w-fit">revitserver1.yourcompany.ru</p>
                                            <p class="text-[12px] md:text-[15px] leading-[150%] font-mono bg-[#F7F7F7] px-2 py-1 rounded w-fit">revitserver2.yourcompany.ru</p>
                                            <p class="text-[12px] md:text-[15px] leading-[150%] font-mono bg-[#F7F7F7] px-2 py-1 rounded w-fit">revitserver3.yourcompany.ru</p>
                                        </div>
                                    </div>
                                </div>
                                <div class="flex items-start gap-2 md:gap-3.5">
                                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">3</p>
                                    <div>
                                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Централизованное управление</p>
                                        <p class="text-[12px] md:text-[15px] leading-[150%]">Объедините все Revit-серверы под корпоративным именем для централизованного управления проектами и повышения узнаваемости бренда.</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <img src="/images/modals/company.png" alt="" class="w-[88px] md:w-[204px] xl:w-[273px] absolute top-0 right-0 md:top-0 md:right-[50px] xl:right-[100px] xl:top-1/2 xl:-translate-y-1/2">
                </div>
                <button @click="$emit('close')" class="mx-auto w-full sm:w-[168px] h-8 md:h-10 rounded-full bg-[#136BFB] text-white flex items-center justify-center text-[13px] md:text-[15px] font-semibold">
                    Подробнее
                </button>
            </div>
        </div>
        <button @click="$emit('close')" class="absolute top-3 right-2.5 md:top-14 md:right-14 xl:right-12">
            <img src="/images/modals/close.svg" alt="" class="w-3 md:w-4">
        </button>
    </div>
</template>

<script setup>
// Определяем события компонента
defineEmits(['close'])
</script>

