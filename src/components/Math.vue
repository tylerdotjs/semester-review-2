<template>
<h1>Math</h1>
  <div class="math">
    <img src="@/assets/aleksTopics.png" alt="Aleks Topics" :hidden="percentActive" @click="percentActive = true">
    <img src="@/assets/aleksPercent.png" alt="Aleks percent" :hidden="!percentActive" @click="percentActive = false">
  </div>
</template>

<script>
export default {
    data(){
        return {
            percentActive: false
        }
    }
}
</script>

<style>
.math {
    display: flex;
    justify-content: center;
    align-content: center;
    width: 100%;
    height: 500px;
}
</style>