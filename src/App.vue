<template>
  <div>
    <Navbar />
    <MoreInfo />
    <AboutUs />
    <OurBest/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from './components/Navbar/Navbar.vue';
import MoreInfo from './components/MoreInfo/MoreInfo.vue';
import AboutUs from './components/BlockAboutUs/AboutUs.vue';
import OurBest from './components/OurBest/OurBest.vue';
import Footer from './components/Footer/Footer.vue'
export default {
  name: 'App',
  components: {
    Navbar,
    MoreInfo,
    AboutUs,
    OurBest,
    Footer
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Merienda:wght@500&display=swap');
@tailwind base;
@tailwind components;
@tailwind utilities;

.container {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
}

@font-face {
    font-family: 'Merienda';
    src: url('../public/Merienda-Regular.ttf') format('ttf');
  }

  body {
    font-family: 'Merienda', cursive;
  }
</style>
