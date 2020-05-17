<template>
  <div class="page">
    <div class="about mt-block">
      <h1 class="title">About me</h1>
      <h2 class="about-title title-md text-bold">
        I'm Nurpais Orozulbaev,
        <br />a creative front-end developer
        <br />based in Bishkek.
      </h2>
      <p
        class="about-text lead"
      >Since 2015, I have been building engaging websites for a diverse range of clients around the world, in locations from Ukraine, Canada & Thailand to Austria, South Korea and even as far as Mexico and America.</p>
      <div class="skills">
        <div class="skills-item">
          <h3 class="lead text-bold">Languages</h3>
          <p
            class="mb-3"
          >I utilize the following programming languages to build the backbone of effeicient, future-proof websites.</p>
          <ul class="skills-lang">
            <li>HTML5</li>
            <li>CSS3</li>
            <li>SCSS</li>
            <li>JavaScript</li>
            <li>Webpack</li>
            <li>Git</li>
          </ul>
        </div>
        <div class="skills-item">
          <h3 class="lead text-bold">Platforms</h3>
          <p class="mb-3">I also use the following platforms and tools.</p>
          <ul class="skills-lang">
            <li>Bootstrap</li>
            <li>Bulma</li>
            <li>Element UI</li>
            <li>GSAP</li>
            <li>Vue/Nuxt</li>
            <li>Express</li>
            <li>NodeJs</li>
            <li>API's</li>
          </ul>
        </div>
        <div class="skills-item">
          <h3 class="lead text-bold">Background</h3>
          <p>I have attained a BSc in Information Technology and an MSc in Web & Mobile Application Development, both from the University of Bishkek. Although I primarilly work as a freelance front-end web developer, I also have agency experience which has enabled me to foster the right mix of theory and practice in my projects.</p>
        </div>
        <div class="skills-item">
          <h3 class="lead text-bold">Let's talk</h3>
          <p>
            I often work with individuals, small businesses and startups buiding anything from brochures, portfolios and blogs to more advanced websites like eCommerce stores. Each project is a collaboration, you'll always have your say and I'll always give an honest opinion on what I think will benefit your business the most. If this sounds like the kind of partnership you'd like,
            <nuxt-link to="contact" class="border-out">don't hesitate to get in touch.</nuxt-link>
          </p>
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