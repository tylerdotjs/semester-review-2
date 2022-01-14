<template>
<div>
  <embed :src="file+'#toolbar=0&navpanes=0&scrollbar=0&view=FitH'" />
</div>
</template>

<script>
export default {
    props: {
        file: String
    }
}
</script>

<style scoped>
    embed {
        width: 60vw;
        max-width: calc(90vh / 1.2941);
        height: calc(60vw * 1.2941);
        max-height: 90vh;
    }
    div {
        display: flex;
        justify-content: center;
    }
</style>