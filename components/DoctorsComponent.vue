<template>
  <section class="doctors">
    <div class="container">
      <h2>NASI LEKARZE</h2>
      <el-row type="flex" class="row-bg" justify="space-around">
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <figure>
              <img src="../assets/img/team1.jpg" alt>
            </figure>
            <figcaption>
              <h4>lek.med.wet.Janusz Wojtaszek</h4>
            </figcaption>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="grid-content bg-purple-light">
            <figure>
              <img src="../assets/img/team2.jpg" alt>
            </figure>
            <figcaption>
              <h4>lek.med.wet.Olaf Wojtaszek</h4>
            </figcaption>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="grid-content bg-purple">
            <figure>
              <img src="../assets/img/team3.jpg" alt>
            </figure>
            <figcaption>
              <h4>lek.med.wet.Zuzanna Myszka</h4>
            </figcaption>
          </div>
        </el-col>
      </el-row>

      
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.el-row {
  margin-bottom: 20px;
  &:last-child {
    margin-bottom: 0;
  }
}
.el-col {
  border-radius: 4px;
  width: 300px;
  padding-bottom: 10px;
  h4 {
    padding: 10px;
    text-align: center;
  }

}
.bg-purple-dark {
  background: #99a9bf;
}
.bg-purple {
  background: #d3dce6;
}
.bg-purple-light {
  background: #e5e9f2;
}
.grid-content {
  border-radius: 4px;
  min-height: 36px;

  figure {
    overflow: hidden;
    padding: 0;
    margin: 0;
    height: 300px;
    border-radius: 5px;

    img {
      transition: all 0.5s;
      &:hover {
        transform: scale(1.1);
      }
    }
  }
}
.row-bg {
  padding: 10px 0;
  background-color: #f9fafc;
}
.doctors {
  background: #f9fafc;
  h2 {
    text-align: center;
  }
  .doctors-content {
    max-width: 1250px;
    margin: 0 auto;
    text-align: center;
    font-weight: bold;
  }
}
</style>


