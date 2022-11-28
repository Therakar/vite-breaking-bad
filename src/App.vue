<script>
 import AppHeader from './components/AppHeader.vue'
 import AppMain from './components/AppMain.vue'
 import AppDropdown from './components/AppDropdown.vue'
  export default {
    components: {
      AppHeader,
      AppMain,
      AppDropdown
    }
  }
</script>

<template>
  <AppHeader />
  <AppDropdown />
  <AppMain />
</template>

<style lang="scss">
  @import './style/global.scss';

  body{
    background-color: var(--primary-color);
  }
</style>
