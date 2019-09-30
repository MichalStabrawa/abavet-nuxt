<template>
  <div>
    <header class="header-about">
      <h2>O NAS</h2>
    </header>
    <section class="about">
      <el-row>
        <el-col :span="16">
          <div class="grid-content bg-purple">
            <p>
              "Pasja, Profesjonalizm, Doświadczenie.
              Diagnostyka, Profilaktyka, Leczenie."
            </p>
            <p>ABA-VET to Przychodnia Weterynaryjna z siedzibą w Wieliczce. To miejsce gdzie lekarze z pasją pomagają zwierzakom. Korzystając z doświadczenia zawodowego i wiedzy zdobytej na szkoleniach i wielu kongresach weterynaryjnych proponujemy najnowsze metody leczenia. Stale poszerzamy swoją wiedzę by Państwa pupile miały możliwość jak najlepszej opieki.</p>
            <p>
              Naszym celem jest stosowanie właściwej profilaktyki, trafne i szybkie diagnozowanie oraz skuteczne leczenie przy wykorzystaniu najnowszej techniki rozpoznawania. Specjalizujemy się głównie w leczeniu psów, kotów i innych małych zwierząt towarzyszących. Trafiają do nas także zwierzęta egzotyczne np. gekony, małpy, alpaki, kangury, oraz ptaki. Do każdego podopiecznego podchodzimy indywidualnie dopasowując, najlepszą strategię leczenia.
              Stosujemy szeroki wachlarz diagnostyki, zabiegów oraz profilaktyki. Współpracujemy z wieloma specjalistami.
            </p>
          </div>
        </el-col>
        <el-col :span="8">
          <div class="grid-content bg-purple-light">
            <figure class="logo-wrapper">
              <img src="../assets/img/petdoctor-logo-green.png" alt />
            </figure>
            <div class="social">
              <span>
                <i class="fa fa-2x fa-facebook-f"></i>
              </span>
              <span>
                <i class="fa fa-2x fa-instagram"></i>
              </span>
              <span>
                <i class="fa fa-2x fa-linkedin"></i>
              </span>
            </div>
          </div>
        </el-col>
      </el-row>
    </section>
    <section class="about-last">
      <h2>DLACZEGO MY?</h2>

      <el-row>
        <el-col :span="12">
          <ul class="about-list">
            <li>
              <span>
                <figure class="icon-wrapper">
                  <img src="../assets/img/icon-dog-and-cat.png" alt />
                </figure>
              </span>

              <span>
                Leczymy głównie psy i koty, oraz także zwierzęta egzotyczne
                i ptaki.
              </span>
            </li>
            <li>
              <span>
                <figure class="icon-wrapper">
                  <img src="../assets/img/icon-award-ribbon.png" alt />
                </figure>
              </span>
              <span>Stale się doszkalamy i rozwijamy. Bierzemy udział w wielu seminariach i kursach.</span>
            </li>
            <li>
              <span>
                <figure class="icon-wrapper">
                  <img src="../assets/img/icon-syringe-med.png" alt />
                </figure>
              </span>
              <span>Nasi lekarze mają wieloletnie doświadczenie oraz są pasjonatami w swoim zawodzie.</span>
            </li>

            <li>
              <span>
                <figure class="icon-wrapper">
                  <img src="../assets/img/house.png" alt />
                </figure>
              </span>
              <span>Wizyty domowe</span>
            </li>
          </ul>
        </el-col>
        <el-col :span="12" class="col-img">
          <figure>
            <img src="../assets/img/dog2.jpeg" alt />
          </figure>
        </el-col>
      </el-row>
      <el-row>
        <el-col>
          <el-button>Sprawdz Nasze Doświadczenie</el-button>
        </el-col>
      </el-row>
    </section>
    <Contact />
  </div>
</template>

<script>
import Contact from "../components/Contact";
export default {
  components: {
    Contact
  }
};
</script>

<style lang="scss" scoped>
.header-about {
  background-image: url("../assets/img/twowet.jpeg");
  height: 250px;
  background-position: center;
  background-size: cover;
  padding: 50px;
  display: flex;
  align-items: center;
}
.about {
  background: #f9fafc;
  padding: 50px;
  h2 {
    text-align: center;
  }
  .logo-wrapper {
    width: 100%;
    img {
      width: 100%;
      -webkit-box-shadow: 0px 6px 5px -6px rgba(0, 0, 0, 0.75);
      -moz-box-shadow: 0px 6px 5px -6px rgba(0, 0, 0, 0.75);
      box-shadow: 0px 6px 5px -6px rgba(0, 0, 0, 0.75);
      padding-bottom: 10px;
    }
  }
}
.about-last {
  padding: 50px;
  figure {
    width: 100%;
    text-align: right img {
      width: 80%;
    }
  }
}
.about-list {
  padding: 0;
  li {
    font-size: 22px;
    list-style-type: none;
    display: flex;
    align-items: center;

    margin-bottom: 30px;
    .icon-wrapper {
      margin-right: 10px;
      background: green;
      border-radius: 5px;
      width: 60px;
      height: 60px;
      display: flex;
      justify-content: center;
      align-items: center;
      img {
        width: 100%;
      }
    }
  }
}
.grid-content {
  padding-right: 20px;
}
button {
  height: 60px;
  box-shadow: 0px 6px 5px -6px rgba(0, 0, 0, 0.75);
  transition: all 0.2s;
  font-size: 20px;
  background: #a4a7ac;
  color: #fff;
  border: 0px;
}
.col-img {
  figure {
    text-align: right;
    img {
      width: 60%;
    }
  }
}
.social{
  height: 100%;
  display: flex;
  justify-content: flex-end;
  padding-top: 10px;
  span{
    margin: 10px;
    width: 60px;
    height: 60px;
    background: #000;
    border-radius: 5px;
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
    transition: all 0.2s;

    &:hover {
      background: #a4a7ac;
    }
  }

}
</style>


