<template>
  <div class="nav">
    <ul class="nav__list">
      <nuxt-link
        tag="div"
        exact
        to="/"
        active-class="nav__activeLink"
        class="nav__listItem"
      >
        Главная
      </nuxt-link>
      <nuxt-link
        tag="div"
        to="/forum"
        active-class="nav__activeLink"
        class="nav__listItem"
      >
        Форум
      </nuxt-link>
      <nuxt-link
        tag="div"
        active-class="nav__activeLink"
        class="nav__listItem"
        to="/news"
      >
        Новости
      </nuxt-link>
      <nuxt-link
        tag="div"
        active-class="nav__activeLink"
        class="nav__listItem"
        to="/media"
      >
        Медиафайлы
      </nuxt-link>
      <nuxt-link
        tag="div"
        active-class="nav__activeLink"
        class="nav__listItem"
        to="/titles"
      >
        Статьи
      </nuxt-link>
      <nuxt-link
        tag="div"
        active-class="nav__activeLink"
        class="nav__listItem"
        to="/info"
      >
        Информация
      </nuxt-link>
    </ul>
    <div class="nav__whiteSpace"></div>
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    
})
</script>
<style lang="scss" scoped>
.nav {
    width: 100%;
    // margin-top: 56px;
    display: flex;
    &__list {
        padding: 0;
        display: flex;
        margin: 0;
        @media screen and (min-width: 729px) and (max-width: 1367px) {
        width: 100%;
        }
    }
    &__listItem {
        padding: 0 2% 1% 2%;
        box-sizing: border-box;
        display: flex;
        width: 119px;
        justify-content: center;
        cursor: pointer;
        height: 100%;
        font-family: Roboto;
        font-size: 16px;
        line-height: 19px;
        color: #3f3e3e;
        border-bottom: 1px solid #c7c7c7;
    }
    &__activeLink {
        color: #008e9f;
        border-bottom: 2px solid #008e9f;
        mix-blend-mode: normal;
    }
    &__whiteSpace {
        border-bottom: 1px solid #c7c7c7;
        width: 100%;
    }
}
</style>