<template>
  <div :class="theme" id="app">
    <HeaderComponent 
      :setLightTheme="setLightTheme" 
      :setDarkTheme="setDarkTheme" 
      :theme="theme" />
    <MainComponent>
      <MembersComponent />
      <DiscordComponent />
      <JoinComponent />
    </MainComponent>
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import MembersComponent from './components/MembersComponent.vue';
import DiscordComponent from './components/DiscordComponent.vue';
import JoinComponent from './components/JoinComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

export default {
  components: {
    HeaderComponent,
    MainComponent,
    MembersComponent,
    DiscordComponent,
    JoinComponent,
    FooterComponent
  }
}
</script>

<style src="@/styles/reset.css"></style>
<style src="@/styles/typography.css"></style>

<style scoped>
  .main, .members__title, .card__title, .card__link, .discord__title, .discord-rules__title, .join__title, .form-button {
    transition: background-color 1.0s ease, color 1.0s ease;
  }

  .light_theme {
    color: var(--text-color-light);
    background-color: var(--bg-color-light);
  }

  .dark_theme {
    color: var(--text-color-dark);
    background-color: var(--bg-color-dark);
  }
</style>

<style>
html, body {
  overflow: hidden; /* Полностью убираем скролл-бар со страницы */
  margin: 0; /* Убираем отступы по краям страницы */
  padding: 0;
  height: 100%;
  width: 100%;
}

#app {
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: column;
}
</style>
