<template>
    <Header></Header>
    <main class="grid-container grow gap-y-[50px] md:gap-y-[70px] mt-7 xl:mt-16 mb-[50px] md:mb-[70px] xl:mb-20 overflow-x-clip">
        <slot/>
    </main>
    <Footer :hide-contact-block="hideFooterContact"></Footer>
</template>

<script setup>
const route = useRoute()

// Получаем параметр из meta страницы
const hideFooterContact = computed(() => {
  return route.meta.hideFooterContact || false
})
</script>