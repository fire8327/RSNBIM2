<template>
    <div class="w-full col-span-full grid-container bg-gradient-to-b from-[#136BFB] to-[#6E99E1] py-9 md:py-14 xl:py-[60px]">
        <div class="flex flex-col gap-10 xl:gap-11">
            <div class="grid grid-cols-3 gap-3.5 xl:gap-5 text-[17px] xl:text-[19px] leading-[25px] font-medium max-md:hidden">
                <div class="rounded-[20px] bg-white flex items-center gap-4 xl:gap-7 py-6 xl:py-7 px-5 xl:px-10">
                    <img src="/images/contacts/phone.svg" alt="" class="w-6">
                    <a target="_blank" href="tel:+74957418963">+7 (495) 741-89-63</a>
                </div>
                <div class="rounded-[20px] bg-white flex items-center gap-4 xl:gap-7 py-6 xl:py-7 px-5 xl:px-10">
                    <img src="/images/contacts/mail.svg" alt="" class="w-6">
                    <div class="relative">
                        <a target="_blank" href="support@rsnbim.ru">support@rsnbim.ru</a>
                        <span class="text-[12px] leading-[100%] text-[#ADADAD] font-medium absolute left-0 -top-2.5">Тех. поддержка</span>
                    </div>
                </div>
                <div class="rounded-[20px] bg-white flex items-center gap-4 xl:gap-7 py-6 xl:py-7 px-5 xl:px-10">
                    <img src="/images/contacts/calendar.svg" alt="" class="w-[22px]">
                    <span>Пн-Пт с 09:00 до 17:00</span>
                </div>
            </div>
        </div>
    </div>
    <div class="flex flex-col gap-10 md:gap-11 xl:gap-9">
        <div class="text-[12px] md:text-[15px] leading-[160%] flex max-md:flex-col gap-1.5 sm:gap-5 md:gap-10 md:justify-between w-full px-3.5 py-4 md:px-9 md:py-5 xl:px-[100px] bg-[#F7F7F7] rounded-[17.5px] md:rounded-[20px]">
            <div class="flex max-md:flex-col md:gap-3 xl:gap-6">
                <img src="/images/contacts/info.png" alt="" class="w-9 h-9 md:w-14 md:h-14">
                <div class="flex flex-col gap-3 md:gap-4 max-md:pl-1">
                    <p>ИП Фадеева Виктория Николаевна</p>
                    <p>ОГРНИП: 324774600362672</p>
                </div>
            </div>
            <div class="flex max-md:flex-col md:gap-4 xl:gap-6">
                <img src="/images/contacts/document.png" alt="" class="w-10 h-10 md:w-12 md:h-12">
                <div class="flex flex-col gap-3 md:gap-4 max-md:pl-1.5">
                    <a href="" class="w-fit underline">Договор-оферта</a>
                    <a href="" class="w-fit underline">Электронный документооборот</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
/* скрытие блок в подвале */
definePageMeta({
  hideFooterContact: true
})
</script>