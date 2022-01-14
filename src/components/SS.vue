<template>
  <h1>Social Studies</h1>

  <h2>Shortages</h2>
  <EmbededPDF :file='require("@/assets/SS/Shortages.pdf")' />

  <h2>Current Event 10/7</h2>
  <EmbededPDF :file='require("@/assets/SS/CE_10_7.pdf")' />
</template>

<script>
import EmbededPDF from './EmbededPDF.vue'

export default {
    components:{
        EmbededPDF
    }
}
</script>

<style scoped>
    h2{
        margin-left: 10vw;
    }
</style>