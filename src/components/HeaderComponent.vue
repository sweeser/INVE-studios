<template>
    <header :class="['header', activeTheme === 'light' ? 'light-header' : 'dark-header']">
        <img class="header__logo" :src="require('@/assets/logo.png')" alt="Logo-site">
        <h1 :class="['header__title', 'typography__h1', activeTheme === 'light' ? 'light-text' : 'dark-text']">INVE STUDIOS</h1>
        <nav class="navigation">
            <ul class="navigation__list">
                <li class="navigation__item">
                    <a :class="['navigation__item-link', 'typography__link', activeTheme === 'light' ? 'light-text' : 'dark-text']" href="#members">Members</a>
                </li>
                <li class="navigation__item">
                    <a :class="['navigation__item-link', 'typography__link', activeTheme === 'light' ? 'light-text' : 'dark-text']" href="#discord">Discord</a>
                </li>
                <li class="navigation__item">
                    <a :class="['navigation__item-link', 'typography__link', activeTheme === 'light' ? 'light-text' : 'dark-text']" href="#join-server">Join server</a>
                </li>
            </ul>
        </nav>
        <ul class="theme-switcher">
            <li class="theme-switcher__item">
                <button 
                    @click="setLightTheme" 
                    :class="['theme-switcher__button', 'theme-switcher__button-type-light', {'active': activeTheme === 'light'}]">
                </button>
            </li>
            <li class="theme-switcher__item">
                <button 
                    @click="setDarkTheme" 
                    :class="['theme-switcher__button', 'theme-switcher__button-type-dark', {'active': activeTheme === 'dark'}]">
                </button>
            </li>
        </ul>
    </header>
</template>

<script>
export default {
    data() {
        return {
            activeTheme: 'light'
        };
    },
    mounted() {
        const savedTheme = localStorage.getItem('theme');
        if (savedTheme) {
            this.activeTheme = savedTheme;
        }
    },
    methods: {
        setLightTheme() {
            this.activeTheme = 'light';
            localStorage.setItem('theme', 'light');
        },
        setDarkTheme() {
            this.activeTheme = 'dark';
            localStorage.setItem('theme', 'dark');
        }
    }
};
</script>

<style src="@/styles/header-styles.css"></style>