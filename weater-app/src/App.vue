<template>
  <div class="flex flex-col min-h-screen font-Montserrat bg-weather-primary">
    <SiteNavigation/>
    <router-view></router-view>
  </div>
</template>

<script setup>
import SiteNavigation from './components/SiteNavigation.vue';

</script>

<style lang="scss" scoped>

</style>