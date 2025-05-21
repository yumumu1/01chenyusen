<template>
  <div class="app">
    <NavBar />
    <HomeSwiper />
    <ContentSection />
    <FooterBar />
    <FeatureHighlights />  
    <ImageTextSection />
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import HomeSwiper from './components/HomeSwiper.vue'
import ContentSection from './components/ContentSection.vue'
import FooterBar from './components/FooterBar.vue'
import FeatureHighlights from './components/FeatureHighlights.vue'
import ImageTextSection from './components/ImageTextSection.vue'

export default {
  components: {
    NavBar,
    HomeSwiper,
    ContentSection,
    FooterBar,
    FeatureHighlights,
    ImageTextSection
  }
}
</script>

<style>
/* 全局样式 */
body {
  margin: 0;
  font-family: Arial, sans-serif;
}
.app {
  margin-bottom: 60px; 
}
button {
  font-family: inherit;
  font-size: 1rem;
}
</style>