<template>
  <div>
    <h1>Posts</h1>
    <Post
      v-for="post of posts"
      :key="post.id"
      :title="post.title"
      :id="post.id"
      :body="post.body"
    />
  </div>
</template>

<script>
import axios from "axios";
import Post from "../../components/post";
export default {
  components: {
    Post: Post
  },
  data() {
    return {
      posts: []
    };
  },
  async created() {
    try {
      const response = await axios.get(
        "https://jsonplaceholder.typicode.com/posts"
      );
      console.log(response);
      this.posts = response.data;
    } catch (error) {
      console.log(error);
    }
  }
};
</script>
