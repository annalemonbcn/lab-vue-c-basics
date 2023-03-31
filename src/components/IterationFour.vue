<template>
  <h2>Iteration 4</h2>
  <p>Here we have a list of posts:</p>
  <PostComp v-for="post in posts" 
  :key="post.id"
  :title="post.title"
  :description="post.description"
  :content="post.content"
  />
</template>

<script>
import PostComp from './PostComp.vue';
export default {
  name: 'IterationFour',
  data() {
    return{
      posts: [
        {
          id: 1,
          title: 'Post 1',
          description: 'Description for post 1',
          content: 'Content for post 1. Lorem ipsum dolor sit amet consectetur adipisicing elit.'
        },
        {
          id: 2,
          title: 'Post 2',
          description: 'Description for post 2',
          content: 'Content for post 2. Lorem ipsum dolor sit amet consectetur adipisicing elit.'
        },
        {
          id: 3,
          title: 'Post 3',
          description: 'Description for post 3',
          content: 'Content for post 3. Lorem ipsum dolor sit amet consectetur adipisicing elit.'
        },
        {
          id: 4,
          title: 'Post 4',
          description: 'Description for post 4',
          content: 'Content for post 4. Lorem ipsum dolor sit amet consectetur adipisicing elit.'
        },
        {
          id: 5,
          title: 'Post 5',
          description: 'Description for post 5',
          content: 'Content for post 5. Lorem ipsum dolor sit amet consectetur adipisicing elit.'
        }
      ]
    }
  },
  components: {
    PostComp,
  }
}
</script>

<style scoped>
.post{
  margin-top: 30px;
}
</style>