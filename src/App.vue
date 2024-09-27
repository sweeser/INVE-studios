<template>
  <div id="app">
    <HeaderComponent />
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

<style lang="scss" src="@/styles/Reset.scss"></style>
<style lang="scss" src="@/styles/typography.scss"></style>

<style scoped>
  #app {
    height: 100%;
    width: 100%;
    display: flex;
    flex-direction: column;
  }

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