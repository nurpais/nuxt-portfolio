<template>
  <div class="page">
    <div class="work mt-block">
      <h1 class="title">My work</h1>
      <div class="works">
        <div class="works-item">
          <a class="works-link" href="https://bit.ly/3aVPQc3">
            <div class="works-img">
              <img src="../assets/images/portf/cinema.jpg" alt />
            </div>
            <div class="works-title title-md text-bold mt-1">Top 10 movies</div>
          </a>
          <div class="works-tag text-gray">
            <span>Vue / GSAP</span>
          </div>
        </div>
      </div>
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