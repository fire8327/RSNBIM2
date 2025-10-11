<template>
    <div class="flex max-sm:flex-col gap-5 sm:justify-between items-center">
        <p class="text-[25px] md:text-[38px] xl:text-[40px] leading-[130%] font-medium">Как пользоваться Revit Server и Accelerator</p>
        <img src="/images/how_use/hero.png" alt="" class="w-full md:max-w-[415px] xl:max-w-[622px]">
    </div>
    <div class="flex flex-col gap-2.5 md:gap-5">
        <MainDropdown 
            title="Как работает Revit Server"
            icon-src="/images/scheme/server.svg"
            icon-class="w-12 md:w-20"
        >
            <div class="flex flex-col gap-4 md:gap-7 xl:gap-10">
                <p class="text-[12px] md:text-[15px] leading-[160%]">Помогает наладить совместную работу коллективов над общими моделями Revit по глобальной сети. Они хранятся на центральном сервере, доступом к которому могут пользоваться все члены группы.</p>
                <div class="flex flex-col gap-9 md:gap-7">
                    <div class="flex flex-col gap-2">
                        <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">Стандартная схема работы</p>
                        <p class="text-[12px] md:text-[15px] leading-[160%]">Рекомендуется чтобы пинги не превышали 40-50 мс от этого зависит скорость синхронизации проекта.</p>
                    </div>
                    <img src="/images/scheme/server-scheme.png" alt="" class="w-full">
                </div>
            </div>
        </MainDropdown>
        <MainDropdown 
            title="Как заказать Revit Server"
            icon-src="/images/how_use/rub.svg"
            icon-class="w-7 md:w-12"
        >
            <div class="flex flex-col gap-3">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">1</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Регистрация, тариф</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Зарегистрируйтесь и выберите нужный вам тариф и роль Revit Server.</p>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">2</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Оплата</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">После оплаты в течении 24 часов вам придет уведомление о готовности сервера.</p>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">3</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Учетные данные для административной панели</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">В письме у вас будет ссылка с учетными данными для входа в административную панель Revit Server и уникальная ссылка для файла RSN.ini и возможности команды работать на общем сервере.</p>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">4</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Папки в административной панели</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Создайте в административной панели папки для проекта, это могут папки с названием проекта и подпапки для работы каждого отдельного инженерного отдела.</p>
                    </div>
                </div>
                <img src="/images/how_use/admin-panel.png" alt="" class="w-full md:max-w-[693px] my-4 mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">5</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Ссылка для участников</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">После создания папок для работы и загрузки моделей в папки Вы можете разослать уникальную ссылку для всех участников проекта для совместной работы или скачать готовый файл RSN.ini в личном кабинете.</p>
                    </div>
                </div>
                <img src="/images/how_use/link.png" alt="" class="w-full md:max-w-[392px] my-4 mx-auto">
                <p class="text-[12px] md:text-[15px] leading-[150%]">Подробнее как подключиться к Revit Server Вы можете узнать на станице <a href="/help" class="text-[#136BFB]">«Помощь»</a></p>
            </div>
        </MainDropdown>
        <MainDropdown 
            title="Как продлить Revit Server"
            icon-src="/images/modals/clock.svg"
            icon-class="w-10 md:w-16"
        >
        <div class="flex flex-col gap-3">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">1</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Уведомление и кнопка «Продлить»</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">За 14 дней до окончания срока аренды Revit Server отправиться уведомление на почту и появится кнопка «Продлить» в личном кабинете. Нажмите кнопку «Продлить».</p>
                    </div>
                </div>
                <img src="/images/how_use/notice.png" alt="" class="w-full md:max-w-[693px] my-4 mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">2</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Срок</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Выберите срок продления.</p>
                    </div>
                </div>
                <img src="/images/how_use/period.png" alt="" class="w-full md:max-w-[392px] my-4 mx-auto">
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">3</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Вкладка «Счета»</p>
                        <p class="text-[12px] md:text-[15px] leading-[150%]">Во вкладке «Счета» автоматически сформируется счет на продление.</p>
                    </div>
                </div>
                <div class="flex items-start gap-2 md:gap-3.5">
                    <p class="w-5 md:w-6 h-5 md:h-6 flex items-center justify-center rounded-full bg-[#136BFB] text-white mt-0.5 text-[12px] md:text-[15px] leading-[100%] font-semibold shrink-0">4</p>
                    <div>
                        <p class="text-[14px] md:text-[21px] leading-[100%] font-semibold">Оплатите счет</p>
                    </div>
                </div>
            </div>
        </MainDropdown>
        <MainDropdown 
            title="Работа Revit Server с Revit Server Accelerator"
            icon-src="/images/scheme/accelerator.svg"
            icon-class="w-9 md:w-14"
        >
            <div class="flex flex-col gap-6">
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">Схема работы</p>
                </div>
                <img src="/images/scheme/accelerator-scheme.png" alt="" class="w-full my-4 mx-auto">
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">Скорость синхронизации проекта</p>
                    <p class="text-[12px] md:text-[15px] leading-[160%]">зависит от времени, которое затрачивается на получение ответа от сервера. Как правило, приемлемый пинг должен быть не выше 40-50 мс. При пинге более 100 мс возникает заметная задержка и время синхронизации проекта с Revit Server может увеличиваться в разы, а при пинге более 170 мс некоторые проекты могут синхронизироваться более часа.</p>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-3 gap-5">
                    <div class="rounded-[13px] md:rounded-[20px] bg-[#F7F7F7] py-4 md:py-6 px-5 md:px-7">
                        <p class="text-[16px] md:text-[23px] leading-[130%] font-semibold">< 40-50 мc</p>
                        <p class="text-[12px] md:text-[15px] leading-[160%]">Приемлемый пинг</p>
                    </div>
                    <div class="rounded-[13px] md:rounded-[20px] bg-[#F7F7F7] py-4 md:py-6 px-5 md:px-7">
                        <p class="text-[16px] md:text-[23px] leading-[130%] font-semibold">> 100 мc</p>
                        <p class="text-[12px] md:text-[15px] leading-[160%]">Пинг, при котором возникает задержка и время синхронизации с Revit Server может увеличиваться в разы</p>
                    </div>
                    <div class="rounded-[13px] md:rounded-[20px] bg-[#F7F7F7] py-4 md:py-6 px-5 md:px-7">
                        <p class="text-[16px] md:text-[23px] leading-[130%] font-semibold">> 170 мc</p>
                        <p class="text-[12px] md:text-[15px] leading-[160%]">Пинг, при котором некоторые проекты могут синхронизироваться более часа. </p>
                    </div>
                </div>
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">Revit Accelerator это ускоритель для Revit</p>
                    <p class="text-[12px] md:text-[15px] leading-[160%]">Который ускоряет процесс загрузки и обновления данных проекта для пользователей, находящихся в удаленных местах от Revit Server`а. Если у вас команда проектировщиков географически удалена от местоположения Revit Server, то рекомендуем дополнительно к Revit Server арендовать Revit Accelerator, который находится географически как можно ближе к специалистам проектной группы.</p>
                </div>
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">Подключение</p>
                </div>
                <img src="/images/how_use/work.png" alt="" class="w-full md:max-w-[693px] my-4 mx-auto">
            </div>
        </MainDropdown>
        <MainDropdown 
            title="Безопасность"
            icon-src="/images/how_use/lock.svg"
            icon-class="w-6 md:w-11"
        >
            <div class="flex flex-col gap-6">
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">Уникальная ссылка</p>
                    <p class="text-[12px] md:text-[15px] leading-[160%]">чтобы разослать ее участникам проекта для совместной работы.</p>
                </div>
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">Ограничение по ip-адресам </p>
                    <p class="text-[12px] md:text-[15px] leading-[160%]">для доступа к вашему Revit Server. По умолчанию Revit Server доступен со всех ip-адресов глобальной сети, при добавлении хотя бы одного ip-адреса в разрешенные, доступ блокируется для всех остальных.</p>
                </div>
                <img src="/images/how_use/safety.png" alt="" class="w-full md:max-w-[693px] my-4 mx-auto">
            </div>
        </MainDropdown>
        <MainDropdown 
            title="Доступ по VPN"
            icon-src="/images/how_use/vpn.svg"
            icon-class="w-10 md:w-16"
        >
            <div class="flex flex-col gap-6">
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">Можете предоставить доступ через VPN</p>
                    <p class="text-[12px] md:text-[15px] leading-[160%]">Одновременно можно использовать доступ по VPN и доступ по ip-адресам или же выбрать только один из них.</p>
                </div>
                <img src="/images/how_use/vpn.png" alt="" class="w-full md:max-w-[693px] my-4 mx-auto">
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">Подключение</p>
                    <p class="text-[12px] md:text-[15px] leading-[160%]">При добавлении доступа по VPN на указанный email приходит подробная инструкция по подключению к вашему Revit серверу.</p>
                </div>
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">Отключение</p>
                    <p class="text-[12px] md:text-[15px] leading-[160%]">При удалении происходит блокировка доступа к Revit серверу в течении 10-15 секунд.</p>
                </div>
            </div>
        </MainDropdown>
        <MainDropdown 
            title="Резервное копирование"
            icon-src="/images/how_use/copy.svg"
            icon-class="w-6 md:w-10"
        >
            <div class="flex flex-col gap-6">
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">3-7 дней - теневое резервное копирование всех проектов</p>
                    <p class="text-[12px] md:text-[15px] leading-[160%]">Ведется на нашем Revit Server по умолчанию глубиной от 3 до 7 дней (в зависимости от используемого места на диске) два раза в сутки в 00-00 и в 12-00. </p>
                </div>
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">Вернуть проект</p>
                    <p class="text-[12px] md:text-[15px] leading-[160%]">Вы можете запросить вернуть проект на определенную дату и время по запросу в техподдержку <br> <a href="https://t.me/rsnbim_support" class="text-[#136BFB]" target="_blank">https://t.me/rsnbim_support</a></p>
                </div>
                <div class="flex flex-col gap-0.5">
                    <p class="text-[16px] md:text-[21px] leading-[130%] font-semibold">14-30 дней - дополнительное резервное копирование всех проектов</p>
                    <p class="text-[12px] md:text-[15px] leading-[160%]">Вы можете приобрести дополнительно  бэкап вашего Revit сервера на 14 или 30 дней.</p>
                </div>
                <img src="/images/how_use/copy.png" alt="" class="w-full md:max-w-[693px] my-4 mx-auto">
            </div>
        </MainDropdown>
    </div>
</template>

<script setup>

</script>