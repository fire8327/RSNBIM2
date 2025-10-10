<template>
    <div @click="$emit('close')" class="fixed inset-0 bg-[#0F0F0F80] z-[9]"></div>
    <div @click.stop class="fixed top-1/2 -translate-y-1/2 left-1/2 -translate-x-1/2 w-[calc(100%-40px)] md:max-w-[825px] xl:max-w-[1118px] z-[10] rounded-[15px] md:rounded-[41px] bg-white shadow-[0px_0.78px_19.48px_3.21px_#0000002B] px-[18px] md:px-[75px] xl:px-[114px] py-6 md:py-6 xl:py-8">
        <div class="flex flex-col gap-4 md:gap-8 xl:gap-6">
            <div class="flex items-center max-xl:flex-col gap-4 md:gap-8 xl:gap-6">
                <div class="flex flex-col gap-4 md:gap-8 xl:gap-6 w-full">
                    <div class="flex flex-col gap-3 md:gap-4 xl:gap-3 w-full">
                        <p class="max-sm:max-w-[179px] md:max-w-[590px] w-full xl:max-w-full text-[18px] md:text-[32px] xl:text-[36px] leading-[130%] font-medium">Используйте свой корпоративный домен!</p>
                        <div class="md:max-w-[454px] xl:max-w-[564px] max-sm:mt-6 rounded-[12px] md:rounded-[30px] flex items-center gap-1 md:gap-3 xl:gap-5 w-fit md:w-full bg-gradient-to-b from-[#136BFB] to-[#6E99E1] text-white py-1 md:py-1.5 xl:py-2.5 px-2 md:px-5 xl:px-6">
                            <img src="/images/modals/icon.png" alt="" class="w-6 md:w-[60px] xl:w-[70px]">
                            <div class="flex flex-col gap-0.5 md:gap-2">
                                <p class="text-[16px] md:text-[18px] leading-[115%] font-semibold">Revit Server под вашим брендом</p>
                                <p class="text-[13px] md:text-[14px] leading-[130%]">чтобы работа в Revit Server стала частью корпоративной экосистемы.</p> 
                            </div>
                        </div>
                    </div>
                    <div class="flex flex-col gap-3 md:gap-4 xl:gap-3 xl:max-w-[564px]">
                        <div class="flex flex-col gap-2.5 md:gap-3 xl:gap-2">
                            <div class="flex items-start gap-3 md:gap-3.5">
                                <p class="w-4 md:w-5 h-4 md:h-5 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[13px] leading-[100%] font-semibold shrink-0">1</p>
                                <div>
                                    <p class="text-[14px] md:text-[16px] leading-[100%] font-semibold">Работайте с Revit Server под вашим брендом</p>
                                    <p class="text-[12px] md:text-[13px] leading-[140%]">Вы можете использовать не только домен rsnbim.ru, но и собственный — например, yourcompany.ru. Это позволит вашим сотрудникам подключаться к проектам через привычный корпоративный адрес.</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-3 md:gap-3.5">
                                <p class="w-4 md:w-5 h-4 md:h-5 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[13px] leading-[100%] font-semibold shrink-0">2</p>
                                <div>
                                    <p class="text-[14px] md:text-[16px] leading-[100%] font-semibold">Корпоративный домен</p>
                                    <p class="text-[12px] md:text-[13px] leading-[140%]">Подключение собственного домена помогает сохранить единый стиль и структуру вашей IT-инфраструктуры. Вместо стандартного адреса вы можете использовать:</p>
                                    <div class="mt-2 flex flex-wrap gap-1">
                                        <p class="text-[11px] md:text-[12px] leading-[140%] font-mono bg-[#F7F7F7] px-1.5 py-0.5 rounded">revitserver1.yourcompany.ru</p>
                                        <p class="text-[11px] md:text-[12px] leading-[140%] font-mono bg-[#F7F7F7] px-1.5 py-0.5 rounded">revitserver2.yourcompany.ru</p>
                                    </div>
                                </div>
                            </div>
                            <div class="flex items-start gap-3 md:gap-3.5">
                                <p class="w-4 md:w-5 h-4 md:h-5 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[13px] leading-[100%] font-semibold shrink-0">3</p>
                                <div>
                                    <p class="text-[14px] md:text-[16px] leading-[100%] font-semibold">Несколько серверов — один бренд</p>
                                    <p class="text-[12px] md:text-[13px] leading-[140%]">Объедините ваши Revit-серверы под корпоративным именем и управляйте проектами централизованно. Это повышает узнаваемость бренда и делает процессы более удобными.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <img src="/images/modals/company.png" alt="" class="w-[70px] md:w-[160px] xl:w-[200px] absolute top-3 right-2 md:top-6 md:right-12 xl:right-[80px] xl:top-1/2 xl:-translate-y-1/2">
            </div>
            <button @click="$emit('close')" class="mx-auto w-full sm:w-[140px] h-7 md:h-8 rounded-full bg-[#136BFB] text-white flex items-center justify-center text-[11px] md:text-[13px] font-semibold gap-1.5">
                <img src="/images/modals/icon.png" alt="" class="w-3 h-3">
                Инструкция
            </button>
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

