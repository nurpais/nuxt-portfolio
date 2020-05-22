<template>
  <div class="container">
    <Loader />
    <Navbar />
    <nuxt />
    <Footer />
  </div>
</template>


<script>
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";
import Loader from "@/components/Loader.vue";

export default {
  components: {
    Navbar,
    Footer,
    Loader
  }
};
</script>