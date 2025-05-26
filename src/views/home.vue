<template>
  <div class="home-container"></div>
</template>

<script>
export default {
  name: 'Home',
  props: {},
  metaInfo: {
    title: 'Serpentine Hopeful Swan',
    meta: [
      {
        property: 'og:title',
        content: 'Serpentine Hopeful Swan',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
</style>
