<template>
    <div class="flex max-sm:flex-col gap-5 sm:justify-between items-center">
        <p class="text-[25px] md:text-[38px] xl:text-[40px] leading-[130%] font-medium">Как пользоваться Revit Server и Accelerator</p>
        <img src="/images/help/hero.png" alt="" class="w-full md:max-w-[450px] xl:max-w-[610px]">
    </div>
    <div class="flex flex-col gap-2.5 md:gap-5">
        <MainDropdown
            title="Как подключиться к Revit Server"
            icon-src="/images/scheme/server.svg"
            icon-class="w-8 md:w-14"
        >
            <div class="flex flex-col gap-5 md:gap-6 xl:gap-10">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">1</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Найти Файл rsn.ini и замените его</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Выберите срок продления, при необходимости резервное копирование, затем нажмите кнопку “Продлить”</p>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">2</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Добавить адрес сервера</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Выберите срок продления, при необходимости резервное копирование, затем нажмите кнопку “Продлить”</p>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">3</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Перезапуск Revit</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Перезапустите Autodesk Revit на своем компьютере, чтобы применить изменения.</p>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">4</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Подключение к Revit Server</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Теперь, когда сервер добавлен в файл rsn.ini, Вы можете подключиться к нему через Revit:</p>
                        <div class="flex flex-col gap-5 mt-5 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="flex items-start gap-2">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Запустите Revit.</p>
                            </div>
                            <div class="flex items-start gap-2">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Выберите в меню "Модели - Открыть..." Перейдите в раздел "Сеть Revit Server". Вы должны увидеть добавленный сервер в списке.</p>
                            </div>
                            <div class="flex items-start gap-2">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Выберите сервер и используйте его для работы с проектами, хранящимися на Revit Server.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </MainDropdown>
        <MainDropdown
            title="Как зайти в административную панель Revit Server"
            icon-src="/images/help/admin.svg"
            icon-class="w-7 md:w-10"
        >
            <div class="flex flex-col gap-5 md:gap-6 xl:gap-10">
                
            </div>
        </MainDropdown>
        <MainDropdown
            title="Как подключиться по VPN"
            icon-src="/images/how_use/vpn.svg"
            icon-class="w-8 md:w-16"
        >
            <div class="flex flex-col gap-5 md:gap-6 xl:gap-10">
                
            </div>
        </MainDropdown>
        <MainDropdown
            title="Начало работы. Как сохранить модель на Revit Server"
            icon-src="/images/help/save.svg"
            icon-class="w-6 md:w-11"
        >
            <div class="flex flex-col gap-5 md:gap-6 xl:gap-10">
                
            </div>
        </MainDropdown>
        <MainDropdown
            title="Централизованное хранение файлов"
            icon-src="/images/help/folder.svg"
            icon-class="w-7 md:w-11"
        >
            <div class="flex flex-col gap-5 md:gap-6 xl:gap-10">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">1</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Ссылка</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Скопируйте ссылку и вставьте ее в проводник Windows.</p>
                    </div>
                </div>
                <img src="/images/help/link.png" alt="" class="w-full md:max-w-[828px] mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">2</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Логин и пароль</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Введите логин и пароль (доступ к общему файл-хранилищу может быть ограничен по ip-адресам или предоставлен через VPN).</p>
                    </div>
                </div>
                <img src="/images/help/login.png" alt="" class="w-full md:max-w-[485px] mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">3</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Привязка файлов</p>
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Сделайте привязку общих файлов через «Диспетчер связей».</p>
                        </div>
                    </div>
                </div>
                <div class="flex flex-col gap-6">
                    <img src="/images/help/connect.png" alt="" class="w-full md:max-w-[598px] mx-auto">
                    <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                        <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                        <p>Используя общее файл-хранилище ссылки на dwg, pdf, ifc и прочие файлы теперь доступны всем участникам проекта. Скорость загрузки и синхронизации проекта должна стать быстрее.</p>
                    </div>
                </div>
            </div>
        </MainDropdown>
        <MainDropdown
            title="Подключение к Revit Accelerator"
            icon-src="/images/scheme/accelerator.svg"
            icon-class="w-8 md:w-14"
        >
            <div class="flex flex-col gap-5 md:gap-6 xl:gap-10">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">1</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Акселератор</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Откройте Revit, в той версии акселератора в которой вы собираетесь работать.</p>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">2</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">«Совместная работа»</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Перейдите на вкладку «Совместная работа» в верхнем меню Revit.</p>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">3</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">«Синхронизация»</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">В разделе «Синхронизация» найдите выпадающее меню и выберите опцию «Управление соединением с Revit Server Accelerator».</p>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">4</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Адрес сервера</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">В появившемся окне введите следующий адрес сервера: адрес вашего сервера.</p>
                    </div>
                </div>
                <img src="/images/help/connect.png" alt="" class="w-full md:max-w-[485px] mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">5</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">«Подключиться»</p>
                        <div class="flex flex-col gap-5 mt-5 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="flex items-start gap-2">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Нажмите "Подключиться".</p>
                            </div>
                            <div class="flex items-start gap-2">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Теперь вы успешно подключены к Revit Accelerator, и можете продолжать работу над проектом с повышенной производительностью и оптимизированным доступом к данным.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </MainDropdown>
    </div>
</template>

<script setup>

</script>