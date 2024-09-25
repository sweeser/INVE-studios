<template>
    <main class="main light_theme">
        <slot></slot>
    </main>
</template>

<script>
export default {
    name: 'MainComponent'
};
</script>

<style scoped>
    .main {
        padding-top: 150px;
        transition: background-color 1.0s ease, color 1.0s ease; /* Плавный переход */
    }
</style>