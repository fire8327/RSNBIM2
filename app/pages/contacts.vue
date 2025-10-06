<template>
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