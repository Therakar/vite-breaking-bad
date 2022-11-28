<!-- MAIN -->
<script>
import AppCounter from './AppCounter.vue'
export default{
  name: "AppMain",
  components: {
    AppCounter,
  }

  }
  
</script>

<template>
    <div class="container">
        <AppCounter />
    </div>
</template>

<style lang="scss" scoped>
    .container{
       
        padding: 3.125rem;
        background-color: var(--secondary-color);
    }
</style>