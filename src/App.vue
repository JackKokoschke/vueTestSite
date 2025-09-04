<script setup>
import AboutSection from "./components/AboutSection.vue";
import ProjectSection from "./components/ProjectSection.vue";
import ReadingSection from "./components/ReadingSection.vue";
import MusicSection from "./components/MusicSection.vue";
import GamingSection from "./components/GamingSection.vue";
import Footer from "./components/Footer.vue";
import NavBar from "./components/NavBar.vue";
</script>

<template>
  <div class="app-container">
    <main class="content-grid">
      <AboutSection />
      <ProjectSection />
      <ReadingSection />
      <MusicSection />
      <GamingSection />
    </main>

    <NavBar />
    <Footer />
  </div>
</template>

<style scoped>
.app-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin: 0 auto;

  max-width: 900px;
  border: blue dotted;
}

.content-grid {
  display: flex;
  flex-direction: column;
  gap: 20px; /* Space between sections */
  width: 100%;
}

.section-box {
  width: 100%;
  aspect-ratio: 5 / 3;
  border: red dotted;
  color: var(--text);
  background-color: var(--bg);
}
</style>
