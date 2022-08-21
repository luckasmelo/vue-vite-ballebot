<template>
    <header class="header">
        <img class="header-image" src="../assets/logo.svg" alt="Logo da comunidade Ballerini">
        <nav class="header-menu">
            <router-link class="header-menu-item" to="#">Comunidade Ballerini</router-link>
            <router-link class="header-menu-item" to="#">Tutorial</router-link>
            <router-link class="header-menu-item" to="#">Open Source</router-link>
            <router-link class="header-menu-item" to="#">Comandos</router-link>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'TheHeader'
}

</script>