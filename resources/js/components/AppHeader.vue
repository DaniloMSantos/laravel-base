<template>
    <header class="header">
        <div class="container">
            <h1 class="logo">Meu Projeto Base</h1>

            <nav>
                <a href="#">Home</a>
                <a href="#">Sobre</a>
                <a href="#">Contato</a>
            </nav>
        </div>
    </header>
</template>

<script setup>
</script>

<style scoped>
.header {
    background: #111827;
    color: white;
}

.container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 16px;

    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav a {
    color: white;
    margin-left: 16px;
    text-decoration: none;
}

nav a:hover {
    text-decoration: underline;
}
</style>
