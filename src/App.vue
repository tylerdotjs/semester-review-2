<template>
  <h1>2021 - 2022 Semester Review</h1>
  <p>Welcome to the Semester Review website of Tyler LaPalm.</p>
  <p>What is a Semester Review? A Semester Review is the showcase of our work at <a href="https://www.denmark.k12.wi.us/schools/academy/">Denmark Viking Academy</a>(VA) in the form of a website.</p>
  <Math />
  <Career />
  <SS />
  <ELA />
  <Other />
 
</template>

<script>
import Career from './components/Career.vue'
import ELA from './components/ELA.vue'
import Math from './components/Math.vue'
import Other from './components/Other.vue'
import SS from './components/SS.vue'

export default {
  name: 'App',
  components: {
    Career,
    Math,
    SS,
    ELA,
    Other
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #b8b8b8;
  width: 70%;
  margin: auto;
}
h1 {
  color: #3cc3f0;
}
.panel {
  background: #4D7499;
  padding: 10px;
  width: 90%;
  height: 100vh;
  margin: auto;
  border-radius: 50px;
}
body {
  background: #093948;
  margin: 0;
}
h2 {
  margin-left: 2rem;
}
p {
  margin-left: 4rem;
}
a {
  color: rgb(122, 122, 255);
}
</style>
