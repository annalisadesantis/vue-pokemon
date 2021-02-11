<template>
  <div class="container">
      <h1>
          {{ title }}
      </h1>
      <h2>
          {{ subtitle }}
      </h2>
  </div>
</template>

<script>

export default {
  name: "CustomTitle",
  props: ['title', 'subtitle']
};
</script>

<style scoped>
h1{
    color: blue;
}
h2{
    color: pink;
}
</style>
