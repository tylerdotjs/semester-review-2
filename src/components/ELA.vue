<template>
  <h1>ELA</h1>

  <EmbededPDF :file="require('@/assets/ELA/NR_SavedByBell.pdf')" />
  <EmbededPDF :file="require('@/assets/ELA/10_26_21_ELA.pdf')" />
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