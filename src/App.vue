<template>
  <Header/>
    <Intro/>
    <Opdracht/>
    <MiddenStuk />
    <Concepten />
    <Footer />
</template>

<script>
import Header from './components/Header.vue'
import Intro from "./components/Intro.vue"
import Opdracht from "./components/Opdracht"
import MiddenStuk from "@/components/MiddenStuk";
import Concepten from "@/components/Concepten";
import Footer from "@/components/Footer";

export default {
  name: 'App',
  components: {
    Header,
    Intro,
    Opdracht,
    MiddenStuk,
    Concepten,
    Footer
  }
}
</script>

<style>
@import "./styles/master.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  overflow-x: hidden;
  background-color: rgba(238, 234, 234, 0.52);
}
</style>
