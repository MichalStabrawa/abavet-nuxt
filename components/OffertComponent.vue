<template>
  <section class="offert">
    <h2>OFERTA</h2>
    <el-row :gutter="20">
      <el-col :span="6">
        <div class="grid-content bg-purple">
          <img src="../assets/img/maintopicon2.png" alt>
        </div>
        <h3 class="offert-title">Rechabilitacja, laseroterapia, tlenoterapia</h3>
      </el-col>
      <el-col :span="6">
        <div class="grid-content bg-purple">
          <img src="../assets//img/maintopicon3.png" alt>
        </div>
        <h3 class="offert-title">Chirurgia twarda i mięka</h3>
      </el-col>
      <el-col :span="6">
        <div class="grid-content bg-purple">
          <img src="../assets/img/maintopicon4.png" alt>
        </div>
        <h3 class="offert-title">Wizyty Domowe</h3>
      </el-col>
      <el-col :span="6">
        <div class="grid-content bg-purple">
          <img src="../assets/img/maintopicon5.png" alt>
        </div>
        <h3 class="offert-title">Dermatologia,cytologia, biopsje, posiewy</h3>
      </el-col>
    </el-row>
    <div class="button-wrapper">
      <el-button type="info">SPRAWDŹ CAŁĄ OFERTĘ</el-button>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.offert {
  padding: 50px;
  padding-bottom: 80px;

  h2 {
    text-align: center;
  }
  .offert-title {
    padding-top: 10px;
    text-align: center;
    font-size: 22px;
  }
  .el-row {
    margin-bottom: 20px;
    &:last-child {
      margin-bottom: 0;
    }
  }
  .el-col {
    border-radius: 4px;
    height: 100%;
  }

  .grid-content {
    border-radius: 4px;
    height: 100%;
    text-align: center;
    background: #447b21;
    img {
      width: 200px;
    }
    figcaption {
      color: #fff;
      padding-bottom: 15px;
      font-size: 18px;
    }
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
  .button-wrapper {
    display: flex;
    justify-content: center;
    margin-top: 80px;

    button {
      height: 60px;
      
      box-shadow: 0px 6px 5px -6px rgba(0, 0, 0, 0.75);
      transition: all 0.2s;
      font-size: 20px;
    }
  }
}
</style>


