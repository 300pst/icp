<template>
  <div id="app" class="app-container">
  <Header />
  <aboutYou />
  <Contact />
  <Skills />
  <projects />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import aboutYou from "./components/aboutYou.vue";
import Contact from "./components/Contact.vue";
import Skills from "./components/Skills.vue";
import projects from "./components/projects.vue";

export default {
  name: "App",
  components: {
    Header,
    aboutYou,
    Contact,
    Skills,
    projects,
  },
};
</script>