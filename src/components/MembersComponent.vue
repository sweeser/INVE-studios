<template>
    <section class="members">
      <h2 id="members" class="members__title typography__h2 light_theme">Members</h2>
      <ul class="members__list">
        <li class="members__list-item">
          <div class="card">
            <img class="card__image" :src="require('@/assets/member-1.jpg')" alt="First member of INVE studios">
            <div class="card__description">
              <h3 class="card__title typography__h3 light_theme">Svyatoslav Shemelin</h3>
              <ul class="card__list">
                <li class="card__list-item"><p class="typography__text">>Graduated from the Federal University of Dubna with a Bachelor's degree</p></li>
                <li class="card__list-item"><p class="typography__text">>He is currently studying at ITMO University in the field of Web Technologies</p></li>
                <li class="card__list-item"><p class="typography__text">>This site is completely designed and developed by this person</p></li>
                <li class="card__list-item"><p class="typography__text">>He is currently looking for a job in the field of front-end developer</p></li>
              </ul>
              <h4 class="card__title_small typography__h4">Portfolio</h4>
              <ul class="card__links">
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">CV</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">hh.ru</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">Cite</a>
                </li>
              </ul>
              <h4 class="card__title_small typography__h4">Contacts</h4>
              <ul class="card__links">
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">Telegram</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">VK</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">GitHub</a>
                </li>
              </ul>
            </div>
          </div>
        </li>
        <li class="members__list-item">
          <div class="card">
            <img class="card__image" :src="require('@/assets/member-2.jpg')" alt="Second member of INVE studios">
            <div class="card__description">
              <h3 class="card__title typography__h3 light_theme">Vladislav Merkulov</h3>
              <ul class="card__list">
                <li class="card__list-item"><p class="typography__text">>Did not graduate from the Moscow Aviation Institute</p></li>
                <li class="card__list-item"><p class="typography__text">>He graduated from another institute, the name of which no one knows</p></li>
                <li class="card__list-item"><p class="typography__text">>He is a team leader in the mobile game development team</p></li>
                <li class="card__list-item"><p class="typography__text">>Currently not looking for a job</p></li>
              </ul>
              <h4 class="card__title_small typography__h4">Portfolio</h4>
              <ul class="card__links">
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">CV</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">hh.ru</a>
                </li>
              </ul>
              <h4 class="card__title_small typography__h4">Contacts</h4>
              <ul class="card__links">
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">Telegram</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">VK</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">GitHub</a>
                </li>
              </ul>
            </div>
          </div>
        </li>
        <li class="members__list-item">
          <div class="card">
            <img class="card__image" :src="require('@/assets/member-3.jpg')" alt="Third member of INVE studios">
            <div class="card__description">
              <h3 class="card__title typography__h3 light_theme">Vladimir Shatohin</h3>
              <ul class="card__list">
                <li class="card__list-item"><p class="typography__text">>Graduated from Kirov University</p></li>
                <li class="card__list-item"><p class="typography__text">>Works in law enforcement agencies</p></li>
                <li class="card__list-item"><p class="typography__text">>Perhaps he will join the army soon</p></li>
                <li class="card__list-item"><p class="typography__text">But he'll be back soon</p></li>
              </ul>
              <h4 class="card__title_small typography__h4">Portfolio</h4>
              <ul class="card__links">
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">CV</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">hh.ru</a>
                </li>
              </ul>
              <h4 class="card__title_small typography__h4">Contacts</h4>
              <ul class="card__links">
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">Telegram</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">VK</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">GitHub</a>
                </li>
              </ul>
            </div>
          </div>
        </li>
        <li class="member-card">
          <div class="card">
            <img class="card__image" :src="require('@/assets/member-4.png')" alt="Fourth member of INVE studios">
            <div class="card__description">
              <h3 class="card__title typography__h3 light_theme">There are some errors</h3>
              <ul class="card__list">
                <li class="card__list-item"><p class="typography__text">>>>Error</p></li>
                <li class="card__list-item"><p class="typography__text">>>>Error</p></li>
                <li class="card__list-item"><p class="typography__text">>>>Error</p></li>
                <li class="card__list-item"><p class="typography__text">>>>Error</p></li>
              </ul>
              <h4 class="card__title_small typography__h4">Portfolio</h4>
              <ul class="card__links">
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">Error</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">Error</a>
                </li>
              </ul>
              <h4 class="card__title_small typography__h4">Contacts</h4>
              <ul class="card__links">
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">Error</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">Error</a>
                </li>
                <li class="card__list-item">
                  <a href="" class="card__link typography__link light_theme">Error</a>
                </li>
              </ul>
            </div>
          </div>
        </li>
      </ul>
    </section>
</template>

<script>
export default {
    name: 'MembersComponent'
};
</script>

<style src="@/styles/members-styles.css"></style>
<style src="@/styles/card.css"></style>