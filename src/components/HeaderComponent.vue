<template>
    <header :class="{'light-header': activeTheme === 'light', 'dark-header': activeTheme === 'dark'}" class="header">
        <img class="header__logo" :src="require('@/assets/logo.png')" alt="Logo-site">
        <h1 class="header__title typography__h1 light_theme">INVE STUDIOS</h1>
        <nav class="navigation">
            <ul class="navigation__list">
                <li class="navigation__item"><a class="navigation__item-link typography__link light_theme" href="#members">Members</a></li>
                <li class="navigation__item"><a class="navigation__item-link typography__link light_theme" href="#discord">Discord</a></li>
                <li class="navigation__item"><a class="navigation__item-link typography__link light_theme" href="#join-server">Join server</a></li>
            </ul>
        </nav>
        <ul class="theme-switcher">
            <li class="theme-switcher__item">
                <button 
                    @click="setLightTheme" 
                    :class="{'active': activeTheme === 'light'}" 
                    class="theme-switcher__button theme-switcher__button-type-light">
                </button>
            </li>
            <li class="theme-switcher__item">
                <button 
                    @click="setDarkTheme" 
                    :class="{'active': activeTheme === 'dark'}" 
                    class="theme-switcher__button theme-switcher__button-type-dark">
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
    methods: {
        setLightTheme() {
            this.activeTheme = 'light';
        },
        setDarkTheme() {
            this.activeTheme = 'dark';
        }
    }
};
</script>

<style src="@/styles/header-styles.css"></style>