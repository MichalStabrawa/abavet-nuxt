<template>
  <footer class="contact">
    <h2>KONTAKT</h2>
    <el-row>
      <el-col :span="8">
        <div class="grid-content home">
          <h3>ABA-VET PRZYCHODNIA WETERYNARYJNA S.C</h3>
          <figure>
            <img src="../assets/img/petdoctor-logo-green.png" alt>
          </figure>
          <address>
            UL.WARZYCKA 37
            <br>32-020 WIELICZKA
            <br>
            <i class="fa fa-phone"></i> 012 278 57 32
            <br>
            <i class="fa fa-fax"></i> tel/fax 12 278 35 11
            <br>
            <i class="fa fa-mobile"></i>
 695 424 252 <br/>
 <i class="fa fa-envelope" aria-hidden="true"> </i> lecznica@lekmedwet.pl
          </address>

          <div class="social-wrapper">
<span><i class="fa fa-2x fa-facebook-f"></i></span>
          <span><i class="fa fa-2x fa-instagram"></i></span>
          <span><i class="fa fa-2x fa-linkedin"></i></span>
          </div>
        </div>
      </el-col>
      <el-col :span="8">
        <div class="grid-content">
          <h3>GODZINY OTWARCIA</h3>
          <div class="hour">
            <p><i class="fa fa-clock-o"></i> poniedziałek</p>
            <p class="hour-item">8-12 i 16-20</p>
          </div>
          <div class="hour">
            <p><i class="fa fa-clock-o"></i> wtorek</p>
            <p class="hour-item">8-12 i 16-20</p>
          </div>
          <div class="hour">
            <p><i class="fa fa-clock-o"></i> środa</p>
            <p class="hour-item">8-12 i 16-20</p>
          </div>
          <div class="hour">
            <p><i class="fa fa-clock-o"></i> czwartek</p>
            <p class="hour-item">8-12 i 16-20</p>
          </div>
          <div class="hour">
            <p><i class="fa fa-clock-o"></i> piątek</p>
            <p class="hour-item">8-12 i 16-20</p>
          </div>
          <div class="hour">
            <p><i class="fa fa-clock-o"></i> sobota</p>
            <p class="hour-item">8-12</p>
          </div>
          <div class="hour">
            <p><i class="fa fa-clock-o"></i> niedziela</p>
            <p class="hour-item">8-12</p>
          </div>
        </div>
      </el-col>
      <el-col :span="8">
        <div class="grid-content">
          <h3>LEKARZE</h3>
          <p>
            <i class="fa fa-user-md"></i> lek.med.wet.Janusz Wojtaszek
          </p>
          <p>
            <i class="fa fa-user-md"></i> lek.med.wet.Olaf Wojtaszek
          </p>
          <p>
            <i class="fa fa-user-md"></i> lek.med.wet.Zuzanna Myszka
          </p>
          <p><i class="fa fa-2x fa-cc-visa" aria-hidden="true"></i> <i class="fa fa-2x fa-cc-mastercard" aria-hidden="true"></i> <i class="fa fa-2x fa-credit-card-alt" aria-hidden="true"></i></p>
        </div>
      </el-col>
    </el-row>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.contact {
  min-height: 200px;
  background: #242424;
  padding: 50px;

  address {
      font-size: 20px;
  }
  h3 {
    margin-bottom: 20px;
  }
  .home {
    figure {
      img {
        width: 200px;
      }
    }
  }
  h2 {
    text-align: center;
    color: #fff;
  }

  .el-row {
    margin-bottom: 20px;
    &:last-child {
      margin-bottom: 0;
    }
  }
  .el-col {
    border-radius: 4px;
  }

  .grid-content {
    border-radius: 4px;
    min-height: 36px;
    color: #fff;
    padding-right: 30px;
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
  .hour {
    display: flex;
    justify-content: space-between;
    padding-right: 20px;
  }
}
.social-wrapper {
  padding-top: 30px;
  display: flex;
span {
  width: 50px;
  height: 50px;
  background: #a4a7ac;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: 10px;
  border-radius: 5px;
}
 
}
</style>


