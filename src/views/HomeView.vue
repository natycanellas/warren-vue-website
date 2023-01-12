<template>
  <div class="home">
    <Navbar :alt="app_name"/>
    <Banner />
    <SectionOne />
    <SectionTwo />
    <Footer />
  </div>
</template>

<script>
  import Navbar from '../components/Navbar.vue';
  import Banner from '../components/Banner.vue'
  import SectionOne from '../components/SectionOne.vue';
  import SectionTwo from '../components/SectionTwo.vue'
  import Footer from '../components/Footer.vue';

  export default {
    name: "Home",
    components: {
      Navbar,
      Banner,
      SectionOne,
      SectionTwo,
      Footer
    }
  }
</script>