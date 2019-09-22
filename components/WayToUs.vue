<template>
  <section class="way-to-us">
      <figure><img src="../assets/img/petdoctor-logo-green.png" alt=""></figure>
    <h2>POSIADAMY PONAD 30 LAT DOŚWIADCZENIA</h2>
  
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.way-to-us {
  height: auto;
  background-image:linear-gradient(to bottom, rgba(250, 250, 250, 0.52), rgba(250, 250, 250, 0.73)),url("../assets/img/abavet-back2.jpeg");
  padding: 50px;
  padding-bottom: 50px;
  height: 450px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;


  h2 {
    text-align: center;
    color: #447B21;
  
  }
  figure {
      img {
          width: 300px;
      }
      margin-bottom: 30px;
  }
}
</style>


