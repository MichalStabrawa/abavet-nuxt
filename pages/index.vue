<template>
<div>
  <Header />
<main>
 <Social/>
</main>
</div>

 
</template>

<script>
import Logo from "~/components/Logo.vue";
import Header from "~/components/Header";
import Social from "~/components/Social"

export default {
  components: {
    Logo,Header,Social
  }
};
</script>

 <style lang="scss" scoped>
.container {
  background: #000;
  h1 {
    color: red;
  }
}
</style>




