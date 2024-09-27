<template>
    <section class="join">
      <h2 id="join-server" class="join__title typography__h2 light_theme">Join server</h2>
      <p class="join__description typography__text">If you want to join our community, then leave a request</p>
      <form class="join-form" action="https://sweeser.github.io/INVE-project/#" method="post">
        <div class="text-field">
          <label class="text-field__label" for="user-first-name">First Name:  </label>
          <input class="text-field__input" type="text" name="first-name" id="user-first-name">
        </div>
        <div class="text-field">
          <label class="text-field__label" for="user-last-name">Last Name: </label>
          <input class="text-field__input" type="text" name="last-name" id="user-last-name">
        </div>
        <div class="text-field">
          <label class="text-field__label" for="user-git-url">Your git url:</label>
          <input class="text-field__input" type="url" name="git-url" id="user-git-url">
        </div>
        <div class="text-field">
          <label class="text-field__label" for="user-email-adress">Your email adress:</label>
          <input class="text-field__input" type="email" name="email-adress" id="user-email-adress">
        </div>
        <div class="text-field">
          <label class="text-field__label" for="comment">Tell us about yourself:</label>
          <textarea class="text-field__input" name="comment" id="comment" rows="5" cols="30" resize="none"></textarea>
        </div>
        <div class="form-buttons">
          <button class="form-button form-button__submit light_theme" type="button">Submit</button>
          <button class="form-button form-button__reset light_theme" type="reset">Reset</button>
        </div>
      </form>
    </section>
</template>

<script>
export default {
  name: 'JoinComponent'
};
</script>

<style lang="scss" src="@/styles/JoinComponent.scss"></style>