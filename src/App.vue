<template>
  <h1>2021 - 2022 Semester Review</h1>
  <p style="margin-left: 100px">Hello, my name is Tyler LaPalm and welcome to my 2021-22 Semester Review Website.</p>
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
</style>
