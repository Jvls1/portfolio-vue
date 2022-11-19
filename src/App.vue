<template>
  <div>
  <!-- ======= Mobile nav toggle button ======= -->
  <!-- <button type="button" class="mobile-nav-toggle d-xl-none"><i class="bi bi-list mobile-nav-toggle"></i></button> -->
  <i class="bi bi-list mobile-nav-toggle d-lg-none"></i>
  <!-- ======= Header ======= -->
  <header-card />

  <!-- ======= Hero Section ======= -->
  <main-container />
  <!-- End Hero -->

  <main id="main">

    <!-- ======= About Section ======= -->
    <about-container />
    <!-- End About Section -->

    <!-- ======= Facts Section ======= -->
    <facts-container />
    <!-- End Facts Section -->

    <!-- ======= Skills Section ======= -->
    <skill-container />
    <!-- End Skills Section -->

    <!-- ======= Resume Section ======= -->
    <resume-container />
    <!-- End Resume Section -->

    <!-- ======= Portfolio Section ======= -->
    <portfolio-container />
    <!-- End Portfolio Section -->

    <!-- ======= Services Section ======= -->
    <!-- End Services Section -->

    <!-- ======= Testimonials Section ======= -->
   <!-- End Testimonials Section -->

    <!-- ======= Contact Section ======= -->
    <contact-container />
   <!-- End Contact Section -->

  </main><!-- End #main -->

  <!-- ======= Footer ======= -->
  <footer-container />
 <!-- End Footer -->

  <div id="preloader"></div>
  </div>
</template>

<script>
import AboutContainer from './components/AboutContainer.vue'
import ContactContainer from './components/ContactContainer.vue'
import FactsContainer from './components/FactsContainer.vue'
import FooterContainer from './components/FooterContainer.vue'
import HeaderCard from './components/HeaderCard.vue'
import MainContainer from './components/MainContainer.vue'
import PortfolioContainer from './components/PortfolioContainer.vue'
import ResumeContainer from './components/ResumeContainer.vue'
import SkillContainer from './components/SkillContainer.vue'

export default {
  name: 'App',
  components: {
    HeaderCard,
    MainContainer,
    AboutContainer,
    FactsContainer,
    SkillContainer,
    ResumeContainer,
    PortfolioContainer,
    ContactContainer,
    FooterContainer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
