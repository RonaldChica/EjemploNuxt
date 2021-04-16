<template>
  <div>
    <Navigation />
    <div class="content">
      <Nuxt />
    </div>
  </div>
</template>

<style>
* {
  box-sizing: border-box;
  color: whitesmoke;
}

body {
  background: #2d3436;
  color: whitesmoke;
  font-family: Arial, Helvetica, sans-serif;
  padding-top: 0;
}

.content {
  padding: 2rem;
}
</style>

<script>
import Navigation from "../components/navigation";
export default {
  components: {
    Navigation
  }
};
</script>
