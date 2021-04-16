<template>
  <h1>welcome to my first nuxt app</h1>
</template>

<script>
export default {
  head() {
    return {
      title: "prueba",
      meta:[{
        hid:"description",
        name:"description",
        content:"website about posts"
      }],
      htmlAttrs:{
        lang:'en'
      }
    };
  }
};
</script>
