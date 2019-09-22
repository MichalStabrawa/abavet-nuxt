<template>
  <section class="about">
    <div class="container">
      <h2 class="about-title">O NAS</h2>

      <div class="content">
          
          <div class="content-item">  <p>ABA-VET to Przychodnia Weterynaryjna z siedzibą w Wieliczce. To miejsce gdzie lekarze z pasją pomagają zwierzakom, korzystając z doświadczenia zawodowego i wiedzy zdobytej na szkoleniach i wielu kongresach weterynaryjnych. Zawsze proponujemy najnowsze metody leczenia. Stale poszerzamy swoją wiedzę by Państwa pupile mieli możliwość jak najlepszej opieki.</p>
        <p>Naszym celem jest stosowanie właściwej profilaktyki, trafne i szybkie diagnozowanie oraz skuteczne leczenie przy wykorzystaniu najnowszej techniki rozpoznawania. Specjalizujemy się głównie w leczeniu psów i kotów oraz innych małych zwierząt towarzyszących ale trafiają do nas także zwierzęta egzotyczne np. gekony, małpy, alpaki, kangury, oraz ptaki. Do każdego podopiecznego podchodzimy indywidualnie dopasowując, najlepszą strategię leczenia.</p>
        <p>
          Współpracujemy z wieloma specjalistami. Stosujemy szeroki wachlarz diagnostyki, zabiegów oraz profilaktyki.
          Weterynarz wieliczka.
        </p></div>
         <div class="content-item"><figure class="content-item__wrapper"><img src="../assets/img/dog-cat.jpeg" alt=""></figure></div>
         
      
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.about-title {
    text-align: center;
}
.content {
    display: flex;

    .content-item {
        &__wrapper {
            width: 100%;
            img {
                width: 100%;
            }
        }
    }

    .content-item:nth-of-type(1) {
width: 70%;
    }
     .content-item:nth-of-type(2){
         width: 30%;
     }
}
</style>


