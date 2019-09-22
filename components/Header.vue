<template>
  <header class="header">
    <div class="header-wrapper">
      <h1>Przychodnia Weterynaryjna ABAVET</h1>
      <h2>Dobry weterynarz Wieliczka</h2>
      <el-button type="info">KONTAKT</el-button>
    </div>
  </header>
</template>

<script>
import ButtonTest from "./ButtonTest";
export default {
  components: {
    ButtonTest
  },
  methods: {
    testMe() {
      alert("Alert Emit");
    }
  }
};
</script>

<style lang="scss" scoped>
.header {
  background: url("../assets/img/abavet-header.jpeg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 666px;
  padding: 50px;

  .header-wrapper {
    h1 {
      margin-bottom: 20px;
      font-size: 42px;
    }
    h2 {
      margin-bottom: 30px;
    }
    .el-button {
      height: 60px;
      width: 200px;
      background: #41771f;
      -webkit-box-shadow: 0px 6px 5px -6px rgba(0, 0, 0, 0.75);
      -moz-box-shadow: 0px 6px 5px -6px rgba(0, 0, 0, 0.75);
      box-shadow: 0px 6px 5px -6px rgba(0, 0, 0, 0.75);
      transition: all 0.2s;
      font-size: 20px;

      &:hover {
        background: #6fb43f;
      }
    }
  }
}
</style>


