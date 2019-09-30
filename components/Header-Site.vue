<template>
  <header class="header-site">
    <slot name="title"></slot>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.header-site {
  background-image: url("../assets/img/twowet.jpeg");
  height: 250px;
  background-position: center;
  background-size: cover;
  padding: 50px;
  display: flex;
  align-items: center;
}
</style>