<template>
  <div class="container">
    <Navbar />
    <Hero />

    <footer class="footer">
      <nuxt-link to="/" class="logo">
        <img src="../assets/images/Nur.svg" alt />
      </nuxt-link>
      <div class="footer-text">Bishkek, Kyrgyzstan</div>
      <ul class="footer-links">
        <li class="border-in">
          <a href="mailto:orozulbaev@gmail.com">orozulbaev@gmail.com</a>
        </li>
        <li class="border-in">
          <a href="https://www.linkedin.com/in/nurpais/">linkedin</a>
        </li>
      </ul>
    </footer>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Hero from "@/components/Hero.vue";

export default {
  components: {
    Navbar,
    Hero
  }
};
</script>