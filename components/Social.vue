<template>
  <section class="social-number">
    <div class="social-number__wrapper">
      <div class="social-number__item">
       <i class="fa fa-phone"></i>
        <span>695 424 252</span>
      </div>
      <figure class="social-figure">
          <img src="../assets/img/petdoctor-logo-green.png" alt="" class="social-figure__img">
      </figure>
      <div class="social-media">
          <span><i class="fa fa-facebook-f"></i></span>
          <span><i class="fa fa-instagram"></i></span>
          
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.social-number {
  margin-top: 5px;
  &__wrapper {
    width: 100%;
    height: 100px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
      height: 100%;
    border-radius: 5px;
    margin-bottom: 30px;
    -webkit-box-shadow: 0px 2px 8px -2px rgba(0, 0, 0, 0.75);
    -moz-box-shadow: 0px 2px 8px -2px rgba(0, 0, 0, 0.75);
    box-shadow: 0px 2px 8px -2px rgba(0, 0, 0, 0.75);
    font-size: 42px;
    padding-left: 50px;
    padding-right: 50px;
    padding-top: 5px;

    .social-figure {
        &__img {
            max-height: 100px;
        }
    }
  }
  &__item {
   
  
   
  }
}
</style>


