<template>
  <div class="root">
    <Hero />
    <section class="pixel mt-block">
      <div class="pixel-info">
        <h2 class="text-bold title-md">I build pixel-perfect web solutions for all devices.</h2>
        <a href="https://cinema-bf2b6.web.app" class="lead border-out">view my work</a>
      </div>
      <img class="pixel-img" src="../assets/images/screen-1.png" alt />
    </section>

    <section class="services mt-block">
      <h2
        class="title services-title"
      >I can take responsibility for one part of your project, or deliver the whole solution.</h2>
      <ul class="services-list">
        <li class="services-item">
          <h3>Web Design & Development</h3>
          <p>I build bespoke, scalable web applications using modern web technologies and tools. I ensure all websites adhere to insustry standards and deliver the best possible user experience.</p>
        </li>
        <li class="services-item">
          <h3>Responsive Design</h3>
          <p>Mobile phones now account for more than half of all internet traffic which is why I ensure that all websites I develop are responsive; this means that the website can adjust to any screen size or device.</p>
        </li>
        <li class="services-item">
          <h3>E-Commerce</h3>
          <p>I utilize powerfull platforms and tools to build scalable, purpose-driven e-Commerce solutions. Your bespoke online store will provide a seamless user experience, that turns leads in to customers.</p>
        </li>
        <li class="services-item">
          <h3>Content Management</h3>
          <p>It's important that you're able to self-manage your website from any place at any time, which is why I develop content management systems that give you control over your website data.</p>
        </li>
        <li class="services-item">
          <h3>Website Management</h3>
          <p>I provide various website management options which include - updating content, backing-up important data, monitoring and security/software updates.</p>
        </li>
        <li class="services-item">
          <h3>SEO</h3>
          <p>Standard on-page SEO practices are included with every website I develop. This allows your website to rank higher in search engine results and potentially drive more traffic to your site.</p>
        </li>
      </ul>
    </section>
    <Together />
  </div>
</template>

<script>
import Hero from "@/components/Hero.vue";
import Together from "@/components/Together.vue";

export default {
  components: {
    Hero,
    Together
  }
};
</script>