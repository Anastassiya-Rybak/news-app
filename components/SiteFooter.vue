<template>
  <div class="site-footer">
    <nav>
      <div class="navbar__logo">
        <nuxt-link no-prefetch to="/">
        </nuxt-link>
      </div>
      <ul>
        <li>
          <nuxt-link exact active-class="active-link" to="/about">О нас</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/contacts">Контакты</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/range">Ассортимент</nuxt-link>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script lang="js">
export default {
  name: 'SiteFooter',
}
</script>

<style lang="css">
</style>