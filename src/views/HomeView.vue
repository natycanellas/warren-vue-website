<template>
  <div class="home">
    <Banner />
    <SectionOne />
    <SectionTwo />
  </div>
</template>

<script>
  import Banner from '../components/Banner.vue'
  import SectionOne from '../components/SectionOne.vue';
  import SectionTwo from '../components/SectionTwo.vue'

  export default {
    name: "Home",
    components: {
      Banner,
      SectionOne,
      SectionTwo
    }
  }
</script>