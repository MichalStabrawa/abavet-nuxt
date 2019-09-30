<template>
  <div>
    <HeaderSite>
      <template v-slot:title>
        <div>
          <h2 class="header-title">OFERTA</h2>
          
        </div>
      </template>
    </HeaderSite>
<section class="separator">
<h3>Zobacz Nasze usługi weterynaryjne</h3>
</section>
    <section class="offert-site">
      <div class="col">
        <img src="../assets//img/derma.jpeg" alt />
      </div>
      <div class="col col-content">
        <h3>PROFILAKTYKA I LECZNICTWO</h3>
        <p>
          szczepienie, odrobaczanie, usuwanie kleszczy, obcinanie pazurków, preparaty przeciwpasożytnicze; na pchły, na kleszcze, preparaty do higieny zębów, krople do oczu, do uszu, lecznicze szampony,
          leczenie kliniczne.
        </p>
      </div>

      <div class="col col-content">
        <h3>DERMATOLOGIA</h3>
        <p>posiewy mykologiczne, pobieranie zeskrobin , preparaty odciskowe skóry, Scotch testy zmian skórnych, barwienie Diff- Quik, cytologia skóry, lampa Wooda</p>
      </div>
      <div class="col">
        <img src="../assets//img/experience.jpeg" alt />
      </div>

      <div class="col">
        <img src="../assets/img/eay.jpeg" alt />
      </div>
      <div class="col col-content">
        <h3>OKULISTYKA</h3>
        <p>fluoresceina, oftalmoskop - badanie dna oka, lampa szczelinowa, chirurgia plastyczna oka.</p>
      </div>
      <div class="col col-content">
        <h3>ZABIEGI HIRURGICZNE</h3>
        <p>bezkrwawe zabiegi wykonywane elektrokauterem, usuwanie guzów, sterylizacje, kastracje, przepukliny, korekcje powiek, usuwanie brodawek, cesarskie cięcia, złamania, amputacje</p>
      </div>
      <div class="col">
        <img src="../assets/img/oper.jpeg" alt />
      </div>
      <div class="col">
        <img src="../assets/img/dog-food.jpeg" alt="">
      </div>
      <div class="col col-content">
        <h3>DIETETYKA</h3>
        <p>ustalanie odpowiedniej karmy dla zwierzęcia, sprzedaż karm dietetycznych, sprzedaż preparatów witaminowych</p>
      </div>
    </section>
    <Contact/>
  </div>
</template>
    


<script>
import HeaderSite from "../components/Header-Site";
import Contact from "../components/Contact";

export default {
  components: {
    HeaderSite,Contact
  }
};
</script>

<style lang="scss" scoped>
.separator {
  height: 100px;
  padding-left: 50px;
  padding-right: 50px;
background: #f9f9f9;
display: flex;
align-items: center;
}
.header-title {
  margin-bottom: 10px;
}
.offert-site {
  
  display: flex;
  flex-wrap: wrap;
  h3 {
    font-size: 32px;
    margin-bottom: 30px;

    &::after {
      margin-top: 10px;
      content: "";
      display: block;
      width: 50px;
      height: 2px;
      background: green;
    }
  }

  .col {
    width: 50%;

    img {
      width: 100%;
      height: 100%;
    }
  }
  .col-content {
    padding: 50px;
  }
}
</style>
