<template>
  <div>
    <h1>about US</h1>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Architecto porro
      quas recusandae suscipit quos dolores ab aliquam quibusdam libero. Et
      error veniam reprehenderit deleniti ab libero voluptates atque aperiam
      unde!
    </p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "prueba",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "website about posts"
        }
      ],
      htmlAttrs: {
        lang: "en"
      }
    };
  }
};
</script>
