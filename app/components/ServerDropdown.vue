<template>
    <div class="flex flex-col w-full bg-white border-[0.7px] border-[#ADADAD] rounded-[16px] md:rounded-[20px] overflow-hidden" :class="{'gap-3.5 md:gap-6' : isDropdownShow}">
        <div @click="isDropdownShow = !isDropdownShow" class="cursor-pointer w-full h-12 md:h-16 flex items-center justify-between px-2.5 md:px-10 xl:px-[70px] bg-[#F7F7F7] rounded-[16px] md:rounded-[20px]">
            <div class="flex items-center gap-1.5 md:gap-5 xl:gap-10">
                <img v-if="serverData.serverType == 'Server'" src="/images/scheme/server.svg" alt="" class="w-8 md:w-14">
                <img v-if="serverData.serverType == 'Accelerator'" src="/images/scheme/accelerator.svg" alt="" class="w-8 md:w-14">
                <p class="text-[16px] md:text-[21px] leading-[100%] font-semibold">{{ serverData?.serverName }}</p>
            </div>
            <div class="flex items-center gap-3">
                <p class="text-[15px] leading-[100%] font-medium text-[#ADADAD] max-md:hidden">Как подключиться</p>
                <div class="w-6 md:w-10 h-6 md:h-10 flex items-center justify-center rounded-full transition-all duration-500" :class="isDropdownShow ? 'bg-[#136BFB]' : 'bg-white rotate-180'">
                    <svg class="w-3 md:w-[19px] transition-all duration-500" :class="isDropdownShow ? 'fill-white' : 'fill-[#ADADAD]'" viewBox="0 0 13 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M5.59452 0.554437C5.95303 0.195925 6.52539 0.195925 6.88391 0.554437L12.0603 5.73085C12.2616 5.93212 12.2616 6.26548 12.0603 6.46675L11.7081 6.81897C11.5068 7.02024 11.1798 7.02024 10.9722 6.81897L6.55055 2.39732C6.38073 2.2275 6.10398 2.2275 5.93416 2.39732L1.51251 6.81897C1.31124 7.02024 0.984173 7.02024 0.776613 6.81897L0.42439 6.46675C0.22312 6.26548 0.22312 5.93212 0.42439 5.73085L5.60081 0.554437H5.59452Z"/>
                    </svg>
                </div>
            </div>
        </div>
        <div class="flex flex-col gap-5 md:gap-10 transition-all duration-500" :class="isDropdownShow ? 'px-4 md:px-20 xl:px-40 pb-8' : 'max-h-0'">
            <div class="flex flex-col gap-3.5">
                <div class="flex flex-col gap-1.5 md:gap-0">
                    <div class="flex items-center gap-2.5 md:gap-3.5">
                        <img src="/images/trial/gear.svg" alt="" class="w-6 md:w-9">
                        <p class="text-[12px] md:text-[15px] leading-[100%] font-semibold">Подключение</p>
                    </div>
                    <div class="flex md:items-center max-md:flex-col gap-1.5 md:gap-6 md:pl-[50px]">
                        <p class="text-[12px] md:text-[15px] leading-[100%]">Пропишите эту ссылку:</p>
                        <div class="flex items-center gap-2 md:gap-3 h-5 md:h-7 px-1.5 md:px-5 bg-[#F7F7F7] rounded-[5px] md:rounded-[7px] w-fit">
                            <p class="text-[12px] md:text-[15px] leading-[100%]">{{ serverData?.connectionLink }}</p>
                            <button>
                                <img src="/images/trial/copy.svg" alt="" class="w-3 md:w-4">
                            </button>
                        </div>
                    </div>
                </div>
                <div class="flex flex-col gap-1.5 md:gap-2 md:pl-[50px]">
                    <p class="text-[12px] md:text-[15px] leading-[100%]">в файле RSN.ini. Он расположен:</p>
                    <div class="inline-flex items-center gap-2 md:gap-3 h-5 md:h-7 px-1.5 md:px-5 bg-[#F7F7F7] rounded-[5px] md:rounded-[7px] w-fit">
                        <p class="text-[12px] md:text-[15px] leading-[100%]">{{ serverData?.fileLocation }}</p>
                        <button>
                            <img src="/images/trial/copy.svg" alt="" class="w-3 md:w-4">
                        </button>
                    </div>
                </div>
            </div>
            <div class="flex flex-col gap-3.5 md:gap-4 md:pl-[50px]">
                <p class="flex items-center justify-center h-6 md:h-[30px] w-[193px] md:w-[247px] rounded-full bg-[#D8E4F9] text-[#136BFB] text-[12px] md:text-[15px] leading-[100%] font-semibold">Административная панель</p>
                <div class="grid grid-cols-2 gap-y-1.5 md:gap-y-2 gap-x-6 md:gap-x-[30px] text-[12px] md:text-[15px] leading-[100%] w-fit">
                    <p class="text-[#ADADAD]">Логин</p>
                    <p>{{ serverData?.login }}</p>
                    <p class="text-[#ADADAD]">Пароль</p>
                    <p>{{ serverData?.password }}</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
// Пропсы
const props = defineProps({
  serverData: {
    type: Object,
    required: true
  }
})

/* показ */
const isDropdownShow = ref(false)
</script>