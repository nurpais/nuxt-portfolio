<template>
  <div class="page">
    <div class="about">
      <h1 class="title">About me</h1>
      <h2 class="about-title title-md text-bold">
        I'm Nurpais Orozulbaev,
        <br />a creative front-end developer <br> based in Bishkek.
      </h2>
      <p
        class="about-text lead"
      >Since 2015, I have been building engaging websites for a diverse range of clients around the world, in locations from Ukraine, Canada & Thailand to Austria, South Korea and even as far as Mexico and America.</p>
    </div>

    <Together />
  </div>
</template>

<script>
import Together from "@/components/Together.vue";
export default {
  components: {
    Together
  }
};
</script>