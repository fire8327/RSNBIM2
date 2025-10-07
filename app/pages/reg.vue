<template>
    <div class="w-full grow col-span-full grid-container md:bg-[#F7F7F7] md:py-12 xl:py-14">
        <div class="md:bg-white md:rounded-[42px] w-full max-w-[1126px] mx-auto md:px-12 md:py-7 xl:px-[120px] xl:py-9 flex flex-col gap-6 md:gap-8 bg-wnite">
            <div class="flex flex-col gap-9 md:gap-11 xl:gap-14">
                <p class="text-[25px] md:text-[35px] xl:text-[40px] font-medium leading-[130%] md:mt-">Регистрация</p>
                <div class="flex flex-col gap-10 md:gap-6">
                    <div class="flex max-sm:flex-col gap-3 md:gap-3.5 xl:gap-4 text-[12px] md:text-[15px]">
                        <button class="w-full sm:w-1/2 h-10 md:h-14 flex items-center justify-center gap-1.5 md:gap-2 bg-[#F7F7F7] rounded-[8px] md:rounded-[11px]">
                            <img src="/images/reg/yandex.svg" alt="" class="w-[22px] md:w-7">
                            <span>Войти через Яндекс</span>
                        </button>
                        <button class="w-full sm:w-1/2 h-10 md:h-14 flex items-center justify-center gap-1.5 md:gap-2 bg-[#F7F7F7] rounded-[8px] md:rounded-[11px]">
                            <img src="/images/reg/vk.svg" alt="" class="w-[22px] md:w-7">
                            <span>Войти через VK</span>
                        </button>
                    </div>
                    <div class="flex items-center w-full gap-1.5 md:gap-2 xl:gap-4">
                        <div class="grow h-[0.5px] bg-[#ADADAD]"></div>
                        <p class="text-[12px] md:text-[15px] leading-[160%] text-[#ADADAD]">или</p>
                        <div class="grow h-[0.5px] bg-[#ADADAD]"></div>
                    </div>
                </div>
            </div>
            <div class="flex flex-col gap-7">
                <div class="flex flex-col gap-1.5 md:gap-2">
                    <p class="text-[13px] md:text-[17px] leading-[100%] font-semibold">ФИО или название организации</p>
                    <input value="Иван Иванов" placeholder="Иван Иванов" type="text" class="flex items-center px-4 xl:px-5 w-full h-8 md:h-10 rounded-[10px] md:rounded-[13px] border-[0.55px] border-[#ADADAD] placeholder:text-[#ADADAD]">
                </div>
                <div class="flex items-center flex-wrap max-sm:flex-col gap-1.5 md:gap-2.5 text-[12px] md:text-[15px]">
                    <label class="group cursor-pointer flex items-center w-full sm:w-fit px-1.5 md:px-2.5 xl:px-3 h-9 md:h-11 gap-1.5 md:gap-2.5 xl:gap-3.5 rounded-[10px] md:rounded-[13px] border-[0.55px] border-[#ADADAD] [&:has(input:checked)]:bg-[#EDF2FB]">
                        <input type="radio" checked class="sr-only" name="person">
                        <div class="w-4 md:w-5 h-4 md:h-5 rounded-full bg-white border-[0.55px] border-[#CDCFD3] p-[1.5px] md:p-0.5">
                            <div class="w-full h-full rounded-full bg-[#136BFB] transition-all duration-500 opacity-0 [.group:has(input:checked)_&]:opacity-100"></div>
                        </div>
                        <span>Физическое лицо</span>
                    </label>
                    <label class="group cursor-pointer flex items-center w-full sm:w-fit px-1.5 md:px-2.5 xl:px-3 h-9 md:h-11 gap-1.5 md:gap-2.5 xl:gap-3.5 rounded-[10px] md:rounded-[13px] border-[0.55px] border-[#ADADAD] [&:has(input:checked)]:bg-[#EDF2FB]">
                        <input type="radio" class="sr-only" name="person">
                        <div class="w-4 md:w-5 h-4 md:h-5 rounded-full bg-white border-[0.55px] border-[#CDCFD3] p-[1.5px] md:p-0.5">
                            <div class="w-full h-full rounded-full bg-[#136BFB] transition-all duration-500 opacity-0 [.group:has(input:checked)_&]:opacity-100"></div>
                        </div>
                        <span>Юридическое лицо</span>
                    </label>
                    <label class="group cursor-pointer flex items-center w-full sm:w-fit px-1.5 md:px-2.5 xl:px-3 h-9 md:h-11 gap-1.5 md:gap-2.5 xl:gap-3.5 rounded-[10px] md:rounded-[13px] border-[0.55px] border-[#ADADAD] [&:has(input:checked)]:bg-[#EDF2FB]">
                        <input type="radio" class="sr-only" name="person">
                        <div class="w-4 md:w-5 h-4 md:h-5 rounded-full bg-white border-[0.55px] border-[#CDCFD3] p-[1.5px] md:p-0.5">
                            <div class="w-full h-full rounded-full bg-[#136BFB] transition-all duration-500 opacity-0 [.group:has(input:checked)_&]:opacity-100"></div>
                        </div>
                        <span class="sm:hidden xl:block">Индивидуальный предприниматель</span>
                        <span class="max-sm:hidden sm:block xl:hidden">ИП</span>
                    </label>
                </div>
            </div>
            <div class="w-full h-[0.39px] bg-[#ADADAD] md:mt-5"></div>
            <div class="flex flex-col gap-3.5 md:gap-4">
                <div class="flex flex-col gap-1.5 md:gap-2.5">
                    <p class="text-[13px] md:text-[17px] leading-[100%] font-semibold">E-mail</p>
                    <input placeholder="Введите e-mail" type="text" class="flex items-center px-4 xl:px-5 w-full h-8 md:h-10 rounded-[10px] md:rounded-[13px] border-[0.55px] border-[#ADADAD] placeholder:text-[#ADADAD]">
                </div>  
                <div class="flex flex-col gap-1.5 md:gap-2.5">
                    <p class="text-[13px] md:text-[17px] leading-[100%] font-semibold">Пароль</p>
                    <input placeholder="Введите пароль" type="text" class="flex items-center px-4 xl:px-5 w-full h-8 md:h-10 rounded-[10px] md:rounded-[13px] border-[0.55px] border-[#ADADAD] placeholder:text-[#ADADAD]">
                </div>  
                <div class="flex flex-col gap-1.5 md:gap-2.5">
                    <p class="text-[13px] md:text-[17px] leading-[100%] font-semibold">Повторите пароль</p>
                    <input placeholder="Введите пароль" type="text" class="flex items-center px-4 xl:px-5 w-full h-8 md:h-10 rounded-[10px] md:rounded-[13px] border-[0.55px] border-[#ADADAD] placeholder:text-[#ADADAD]">
                </div>  
            </div>
            <div class="flex flex-col gap-1.5 md:gap-2.5 mt-3.5 md:-mt-1 text-[10px] md:text-[13px] leading-[120%] text-[#ADADAD]">
                <label class="group cursor-pointer flex items-start gap-2 md:gap-2.5 xl:gap-4">
                    <input type="checkbox" class="sr-only">
                    <div class="transition-all duration-500 flex items-center justify-center w-4 h-4 shrink-0 rounded-[4px] border-[0.8px] border-[#D0D0D0] bg-[#E3E3E3] opacity-40 [.group:has(input:checked)_&]:opacity-100 [.group:has(input:checked)_&]:bg-[#136BFA] [.group:has(input:checked)_&]:border-[#136BFA]">
                        <img src="/images/reg/check.svg" alt="" class="transition-all duration-500 opacity-0 [.group:has(input:checked)_&]:opacity-100">
                    </div>
                    <p>Согласен с <a href="" target="_blank" class="underline">пользовательским соглашением</a> и <a href="" target="_blank" class="underline">договором оферты</a> и <a href="" target="_blank" class="underline">правилами пользования услугами</a></p>
                </label>
                <label class="group cursor-pointer flex items-start gap-2 md:gap-2.5 xl:gap-4">
                    <input type="checkbox" class="sr-only">
                    <div class="transition-all duration-500 flex items-center justify-center w-4 h-4 shrink-0 rounded-[4px] border-[0.8px] border-[#D0D0D0] bg-[#E3E3E3] opacity-40 [.group:has(input:checked)_&]:opacity-100 [.group:has(input:checked)_&]:bg-[#136BFA] [.group:has(input:checked)_&]:border-[#136BFA]">
                        <img src="/images/reg/check.svg" alt="" class="transition-all duration-500 opacity-0 [.group:has(input:checked)_&]:opacity-100">
                    </div>
                    <p>Согласен на <a href="" target="_blank" class="underline">обработку персональных данных</a></p>
                </label>
            </div>
            <div class="flex flex-col gap-2 md:gap-2.5 items-center mx-auto">
                <button class="w-full sm:w-[168px] text-white h-8 md:h-11 flex items-center justify-center rounded-full bg-[#136BFB] text-[13px] md:text-[15px] leading-[100%] font-semibold">Регистрация</button>
                <a href="/auth" class="text-[12px] md:text-[15px] leading-[100%] underline text-[#ADADAD]">Уже есть аккаунт?</a>
            </div>
        </div>
    </div>
</template>

<script setup>
/* скрытие блока в подвале */
definePageMeta({
  hideFooterContact: true
})
</script>