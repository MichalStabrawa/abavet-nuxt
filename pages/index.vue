<template>
  <div>
    <Header/>
    <main>
      <Social/>
      <AboutComponent />
      <DoctorsComponent />
      <FixSection />
      <OffertComponent />
      <WayToUs />
     
    </main>
    <Contact />
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import Header from "~/components/Header";
import Social from "~/components/Social";
import AboutComponent from "~/components/AboutComponent";
import DoctorsComponent from "~/components/DoctorsComponent";
import FixSection from "~/components/FixSection";
import OffertComponent from "~/components/OffertComponent";
import WayToUs from "~/components/WayToUs";
import Contact from "~/components/Contact"

export default {
  components: {
    Logo,
    Header,
    Social,
    AboutComponent,
    DoctorsComponent,
    OffertComponent,
    FixSection,
    WayToUs,
    Contact
  }
};
</script>

 <style lang="scss" scoped>
.container {
  background: #000;
  h1 {
    color: red;
  }
 
}


</style>




