<template>
    <div class="flex max-sm:flex-col gap-5 sm:justify-between items-center">
        <p class="text-[25px] md:text-[38px] xl:text-[40px] leading-[130%] font-medium">Помощь</p>
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
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">1</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Меню информации о сервере</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Перейдите в меню информации о Revit Server нажав на имя сервера.</p>
                    </div>
                </div>
                <img src="/images/help/menu.png" alt="" class="w-full md:max-w-[414px] mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">2</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Логин и пароль</p>
                        <div class="flex flex-col gap-5">
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>В "Информации о сервере" нажмите глазок и вам откроется логин, пароль для входа в административную панель и ссылка.</p>
                            </div>
                            <img src="/images/help/login2.png" alt="" class="w-full md:max-w-[828px] mx-auto">
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Кликните на ссылку и вам откроется новая страница с логином и паролем.</p>
                            </div>
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Введите логин пароль</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">3</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Административная панель</p>
                        <div class="flex flex-col gap-5">
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Вы попадете в Административную панель Revit Server. Она предоставляет различные функции для управления и мониторинга Revit Server.</p>
                            </div>
                            <img src="/images/help/panel.png" alt="" class="w-full md:max-w-[693px] mx-auto">
                            <p class="text-[12px] md:text-[15px] leading-[150%] font-semibold">Функции</p>
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Просмотр списка всех проектов, хранящихся на сервере.</p>
                            </div>
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Создание новых проектов и папок.</p>
                            </div>
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Удаление существующих проектов и папок.</p>
                            </div>
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Управление доступом к проектам и папкам.</p>
                            </div>
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Просмотр текущего состояния сервера и его ресурсов.</p>
                            </div>
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Просмотр журналов событий и логов операций для отслеживания активности на сервере.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </MainDropdown>
        <MainDropdown
            title="Как подключиться по VPN"
            icon-src="/images/how_use/vpn.svg"
            icon-class="w-8 md:w-16"
        >
            <div class="flex flex-col gap-5 md:gap-6 xl:gap-10">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">1</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">VPN клиент WireGuard</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Скачайте и установите по ссыlке <a class="text-[#136BFB]" target="_blank">VPN клиент WireGuard.</a></p>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">2</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Конфигурация туннеля</p>
                        <div class="flex flex-col gap-5">
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Во вложении присланного письма находится конфигурация туннеля для доступа к VPN серверу.</p>
                            </div>
                            <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                                <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                                <p>Откройте приложение WireGuard и нажмите «Добавить туннель» и выберите архив из письма.</p>
                            </div>
                        </div>
                        <img src="/images/help/tunnel.png" alt="" class="w-full md:max-w-[393px] my-4 mx-auto">
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Добавиться туннель для подключения к Revit серверу.</p>
                        </div>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">3</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Подключить</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Нажмите кнопку «Подключить».</p>
                    </div>
                </div>
                <img src="/images/help/plug.png" alt="" class="w-full md:max-w-[693px] mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">4</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Сервер в файл RSN.ini</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Если у вас был ранее добавлен сервер в файл RSN.ini, то можете приступать к работе в Revit. Если нет, то прочтите «Как подключиться к Revit Server».</p>
                    </div>
                </div>
            </div>
        </MainDropdown>
        <MainDropdown
            title="Начало работы. Как сохранить модель на Revit Server"
            icon-src="/images/help/save.svg"
            icon-class="w-6 md:w-11"
        >
            <div class="flex flex-col gap-5 md:gap-6 xl:gap-10">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">1</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Вкладка «Совместная работа»</p>
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Выбираем вкладку «Совместная работа»</p>
                        </div>
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Кликаем на «Совместная работа» в панели</p>
                        </div>
                    </div>
                </div>
                <img src="/images/help/joint_work.png" alt="" class="w-full md:max-w-[828px] mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">2</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">«В вашей сети»</p>
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Выбираем «В вашей сети»</p>
                        </div>
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Соглашаемся</p>
                        </div>
                    </div>
                </div>
                <img src="/images/help/network.png" alt="" class="w-full md:max-w-[440px] mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">3</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">«Рабочие наборы»</p>
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Проверяем, что стала активна кнопка «Рабочие наборы»</p>
                        </div>
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Ок</p>
                        </div>
                    </div>
                </div>
                <img src="/images/help/working_sets.png" alt="" class="w-full md:max-w-[828px] mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">4</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Сохранить проект</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Файл – Сохранить как и сохраняем проект на Revit Server</p>
                    </div>
                </div>
                <img src="/images/help/save_project.png" alt="" class="w-full md:max-w-[828px] mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">5</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">«Считать моделью из хранилища»</p>
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Заходим в Параметры и проверяем, что появилась галочка напротив пункта «Считать моделью из хранилища»</p>
                        </div>
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Ок</p>
                        </div>
                    </div>
                </div>
                <img src="/images/help/model.png" alt="" class="w-full md:max-w-[693px] mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">6</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Сохранить</p>
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>После нажатия Сохранить, станет активной кнопка синхронизации.</p>
                        </div>
                        <div class="flex items-start gap-2 text-[12px] md:text-[15px] leading-[150%]">
                            <div class="w-0.5 h-0.5 rounded-full bg-[#0F0F0F] shrink-0 mt-2 md:mt-3"></div>
                            <p>Сохранить</p>
                        </div>
                    </div>
                </div>
                <img src="/images/help/save2.png" alt="" class="w-full md:max-w-[485px] mx-auto">
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
                    <img src="/images/help/binding.png" alt="" class="w-full md:max-w-[598px] mx-auto">
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