<template>
    <div class="fixed inset-0 bg-[#0F0F0F80] z-[9]"></div>
    <div class="fixed top-1/2 -translate-y-1/2 left-1/2 -translate-x-1/2 w-[calc(100%-40px)] md:max-w-[825px] xl:max-w-[1118px] z-[10] rounded-[15px] md:rounded-[41px] bg-white shadow-[0px_0.78px_19.48px_3.21px_#0000002B] px-[18px] md:px-[75px] xl:px-[114px] py-6 md:py-10 xl:py-14">
        <div class="flex flex-col gap-5 md:gap-14 xl:gap-10">
            <div class="flex flex-col gap-4 md:gap-7 xl:gap-5">
                <p class="max-w-[179px] md:max-w-[590px] xl:max-w-full text-[20px] md:text-[40px] leading-[130%] font-medium">Попробуйте сервис RSNBIM бесплатно!</p>
                <div class="rounded-[12px] md:rounded-[30px] flex items-center gap-1 md:gap-3 xl:gap-5 w-fit xl:w-full bg-gradient-to-b from-[#136BFB] to-[#6E99E1] text-white py-1 md:py-1.5 xl:py-2.5 px-1.5 md:px-5 xl:px-6">
                    <img src="/images/trial/calendar.svg" alt="" class="w-7 md:w-[71px] xl:w-[87px]">
                    <div class="flex flex-col gap-0.5 md:gap-2">
                        <p class="text-[14px] md:text-[21px] leading-[115%] font-semibold">7 дней тестовый период</p>
                        <p class="text-[12px] md:text-[15px] leading-[130%]">чтобы вы могли оценить работу сервиса</p> 
                    </div>
                </div>
            </div>
            <div class="flex flex-col gap-4 md:gap-7 xl:gap-11">
                <div class="flex flex-col gap-2 md:gap-4 xl:gap-5">
                    <div class="flex items-start gap-2 md:gap-3.5">
                        <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold">1</p>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Зарегистрируйтесь на сайте</p>
                    </div>
                    <div class="flex items-start gap-2 md:gap-3.5">
                        <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold">2</p>
                        <div>
                            <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Создайте сервер</p>
                            <p class="text-[12px] md:text-[15px] leading-[150%]">с нужными характеристиками и в выбранной локации</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-2 md:gap-3.5">
                        <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold">3</p>
                        <div>
                            <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Счет оплачивать не нужно</p>
                            <p class="text-[12px] md:text-[15px] leading-[150%]">просто напишите в техподдержку в <a href="https://t.me/rsnbim_support" target="_blank" class="text-[#136BFB]">Telegram @rsnbim_support</a>, что вам нужен тестовый период</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-2 md:gap-3.5">
                        <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold">4</p>
                        <div>
                            <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Если сервис вас устроит</p>
                            <p class="text-[12px] md:text-[15px] leading-[150%]">оплачиваете счет и продолжаете работать без перерывов</p>
                        </div>
                    </div>
                </div>
                <div class="flex items-start md:items-center gap-1 md:gap-4 bg-[#D8E4F9] py-1 px-1 md:py-3.5 md:px-4 xl:px-5 xl:py-4 rounded-[10px] md:rounded-[18px]">
                    <img src="/images/trial/clock.svg" alt="" class="w-8 md:w-[50px]">
                    <div class="flex flex-col gap-1 md:gap-0">
                        <p class="text-[14px] md:text-[21px] leading-[120%] font-semibold">Сервер будет готов в течение 30 минут,</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">а данные для входа придут на вашу почту.</p>
                    </div>
                </div>
            </div>
            <a href="/reg" class="mx-auto w-full sm:w-[168px] h-8 md:h-10 rounded-full bg-[#136BFB] text-white flex items-center justify-center text-[13px] md:text-[15px] font-semibold">Регистрация</a>
        </div>
        <img src="/images/trial/close.svg" alt="" class="w-3 md:w-4 absolute top-3 right-2.5 md:top-14 md:right-14 xl:right-12">
    </div>
</template>

<script setup>

</script>