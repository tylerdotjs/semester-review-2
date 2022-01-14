<template>
  <h1>Other</h1>
  <EmbededPDF :file="require('@/assets/cupStacking.pdf')" />
  <ul>
    <li>Civics RVA</li>
  </ul>
</template>

<script>
import EmbededPDF from './EmbededPDF.vue'

export default {
    components:{
        EmbededPDF
    }
}
</script>

<style>

</style>