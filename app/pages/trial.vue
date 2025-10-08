<template>
    <div class="flex max-sm:flex-col gap-10 md:gap-6 md:justify-between items-center">
        <p class="text-[25px] md:text-[38px] xl:text-[40px] leading-[130%] font-medium">
            <span class="inline-flex gap-1 md:gap-4 whitespace-nowrap">Добро пожаловать <img src="/images/trial/hand.svg" alt="" class="w-6 md:w-12"></span> <br> 
            на страницу пробного тестирования облачного сервера Revit!
        </p>
        <img src="/images/trial/hero.png" alt="" class="w-full sm:w-[280px] md:w-[360px] xl:w-[534px]">
    </div>
    <div class="flex flex-col gap-9 md:gap-12 xl:gap-9">
        <div class="flex flex-col items-center text-center gap-0.5 md:gap-2">
            <p class="text-[12px] md:text-[17px] leading-[100%] font-medium text-[#136BFB]">Как подключиться?</p>
            <p class="text-[23px] md:text-[35px] leading-[120%] md:leading-[100%] font-medium">Серверы для подключения</p>
        </div>
        <div class="flex flex-col gap-1.5 md:gap-4">
            <ServerDropdown 
              v-for="server in serversData" 
              :key="server.serverName"
              :server-data="server" 
            />
        </div>
    </div>
</template>

<script setup>
// Данные для серверов
const serversData = [
  {
    serverName: 'Revit Server 2026',
    serverType: 'Server',
    connectionLink: 'Revit Server: trial.rsnbim.ru',
    fileLocation: 'C:\\ProgramData\\Autodesk\\Revit Server 2026\\Config\\rsn.ini',
    login: 'AdminRS',
    password: '98uioy89h8AA09'
  },
  {
    serverName: 'Revit Server 2025',
    serverType: 'Server',
    connectionLink: 'Revit Server: trial2025.rsnbim.ru',
    fileLocation: 'C:\\ProgramData\\Autodesk\\Revit Server 2025\\Config\\rsn.ini',
    login: 'Admin2025',
    password: 'Kj9mN2pQ8vX'
  },
  {
    serverName: 'Revit Server 2024',
    serverType: 'Accelerator',
    connectionLink: 'Accelerator: acc2024.rsnbim.ru',
    fileLocation: 'C:\\ProgramData\\Autodesk\\Revit Server 2024\\Config\\rsn.ini',
    login: 'AccAdmin',
    password: 'B7nR3sT6wY'
  },
  {
    serverName: 'Revit Server 2023',
    serverType: 'Server',
    connectionLink: 'Revit Server: trial2023.rsnbim.ru',
    fileLocation: 'C:\\ProgramData\\Autodesk\\Revit Server 2023\\Config\\rsn.ini',
    login: 'Admin2023',
    password: 'M4qL8uI1oP'
  },
  {
    serverName: 'Revit Server 2022',
    serverType: 'Accelerator',
    connectionLink: 'Accelerator: acc2022.rsnbim.ru',
    fileLocation: 'C:\\ProgramData\\Autodesk\\Revit Server 2022\\Config\\rsn.ini',
    login: 'Acc2022',
    password: 'F9hJ2kL5nM'
  },
  {
    serverName: 'Revit Server 2021',
    serverType: 'Server',
    connectionLink: 'Revit Server: trial2021.rsnbim.ru',
    fileLocation: 'C:\\ProgramData\\Autodesk\\Revit Server 2021\\Config\\rsn.ini',
    login: 'Admin2021',
    password: 'D6vC3xZ7aB'
  },
  {
    serverName: 'Revit Server 2020',
    serverType: 'Accelerator',
    connectionLink: 'Accelerator: acc2020.rsnbim.ru',
    fileLocation: 'C:\\ProgramData\\Autodesk\\Revit Server 2020\\Config\\rsn.ini',
    login: 'Acc2020',
    password: 'G8wE4rT1yU'
  },
  {
    serverName: 'Revit Server 2019',
    serverType: 'Server',
    connectionLink: 'Revit Server: trial2019.rsnbim.ru',
    fileLocation: 'C:\\ProgramData\\Autodesk\\Revit Server 2019\\Config\\rsn.ini',
    login: 'Admin2019',
    password: 'H5iO9pA2sD'
  }
]
</script>