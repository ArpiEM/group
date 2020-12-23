<template>
    <div class="container-settings-left row">
        <nuxt-link
            tag="div"
            exact
            to="/forum/configurations"
            active-class="nav__activeLink"
            class="nav__listItem"
        > 
            <button class="settings-btn left pointer">Настройки</button>
        </nuxt-link>
          <nuxt-link
            tag="div"
            exact
            to="/forum/configurations/categories"
            active-class="nav__activeLink"
            class="nav__listItem"
        > 
            <button class="settings-btn left pointer">Категории</button>
        </nuxt-link>
          <nuxt-link
            tag="div"
            exact
            to="forum/configurations/settings"
            active-class="nav__activeLink"
            class="nav__listItem"
        > 
            <button class="settings-btn left pointer">Форум</button>
        </nuxt-link>
    </div>
</template>