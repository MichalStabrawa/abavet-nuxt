<template>
  <div>
    <HeaderSite>
      <template v-slot:title>
        <div>
          <h2 class="header-title">KONTAKT</h2>
        </div>
      </template>
    </HeaderSite>

    <section class="contact-main">
      <el-row>
        <el-col :span="12">
          <div class="contact-items">
            <span class="icons">
              <i class="fa  fa-phone"></i>
            </span><span>012 278 57 32</span>
          </div>
            <div class="contact-items">
            <span class="icons">
              <i class="fa fa-mobile"></i>
            </span><span>695 424 252</span>
          </div>
           <div class="contact-items">
            <span class="icons">
              <i class="fa fa-fax"></i>
            </span><span>012 278 57 32</span>
          </div>
            <div class="contact-items">
            <span class="icons">
              <i class="fa fa-envelope"></i>
            </span><span>012 278 57 32</span>
          </div>
        </el-col>
        <el-col :span="12">1</el-col>
      </el-row>
    </section>
    <Contact />
  </div>
</template>

<script>
import HeaderSite from "../components/Header-Site";
import Contact from "../components/Contact";
export default {
  components: {
    HeaderSite
  }
};
</script>

<style lang="scss" scoped>
.contact-main {
       background: #6fb43f;
  .el-col-12:nth-child(1) {
 
    padding: 50px;
  }
  .el-col-12 {
      
      height: 100%;
  }
  .contact-items {
      font-size: 26px;
      color: #fff;
      display: flex;
      width: 100%;
      align-items: center;
      margin-bottom: 20px;

      .icons {
          display: flex;
          justify-content: center;
          align-items: center;
          width: 50px;
          height: 50px;
          margin-right:10px;
          background: #000;
          border-radius: 50%;
      }
  }
}
</style>
    
