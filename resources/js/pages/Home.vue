<template>
    <div class="page">
        <AppHeader />

        <HomeContent />

        <AppFooter />
    </div>
</template>

<script setup>
import AppHeader from '../components/AppHeader.vue';
import AppFooter from '../components/AppFooter.vue';
import HomeContent from '../components/HomeContent.vue';
</script>

<style scoped>
.page {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}
</style>
