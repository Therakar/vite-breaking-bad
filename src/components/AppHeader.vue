<!-- HEADER -->
<script>
export default{
  name: "AppHeader"
}

</script>

<template>
  <div class="title d-flex align-items-center">
    <img src="../assets/logo.png" alt="logo">
    <h1>Breaking Bad Api</h1>
  </div>
</template>

<style lang="scss" scoped>
  .title{
    max-height: 80px;
    padding: 20px;
    img {
      width: 50px;
      margin-right: 10px;
    }
    h1{
      color: var(--secondary-color);
    }
  }
</style>