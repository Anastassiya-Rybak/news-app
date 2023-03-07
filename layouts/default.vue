<template>
  <div>
    <SiteHeader />
    <div class="page-content">
      <div class="container">
        <nuxt/>
      </div>
    </div>
    <SiteFooter />
  </div>
</template>

<script lang="js">
import SiteHeader from '~/components/SiteHeader.vue';
import SiteFooter from '~/components/SiteFooter.vue';

export default {
  components: {
    SiteHeader,
    SiteFooter
}
}
</script>

<style>

</style>