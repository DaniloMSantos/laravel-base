<template>
    <footer class="footer">
        <p>© {{ year }} - Meu Projeto Base</p>
    </footer>
</template>

<script setup>
const year = new Date().getFullYear();
</script>

<style scoped>
.footer {
    background: #f3f4f6;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
    color: #4b5563;
}
</style>
