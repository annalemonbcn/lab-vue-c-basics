<template>
  <div class="post">
    <h3>{{ title }}</h3>
    <p>{{ description }}</p>
    <p>{{ content }}</p>
  </div>
</template>

<script>
export default {
  name: 'PostComp',
  props: {
    title: {
      type: String,
      required: true
    },
    description:{
      type: String,
      required: true
    },
    content:{
      type: String,
      required: true
    },
    // posts: [
    //   {
    //     id: 1,
    //     title: 'Post 1',
    //     description: 'Description for post 1',
    //     content: 'Content for post 1. Lorem ipsum dolor sit amet consectetur adipisicing elit.'
    //   },
    //   {
    //     id: 2,
    //     title: 'Post 2',
    //     description: 'Description for post 2',
    //     content: 'Content for post 2. Lorem ipsum dolor sit amet consectetur adipisicing elit.'
    //   },
    //   {
    //     id: 3,
    //     title: 'Post 3',
    //     description: 'Description for post 3',
    //     content: 'Content for post 3. Lorem ipsum dolor sit amet consectetur adipisicing elit.'
    //   },
    //   {
    //     id: 4,
    //     title: 'Post 4',
    //     description: 'Description for post 4',
    //     content: 'Content for post 4. Lorem ipsum dolor sit amet consectetur adipisicing elit.'
    //   },
    //   {
    //     id: 5,
    //     title: 'Post 5',
    //     description: 'Description for post 5',
    //     content: 'Content for post 5. Lorem ipsum dolor sit amet consectetur adipisicing elit.'
    //   }
    // ]
  }
}
</script>

<style>
.post{
  margin-top: 30px;
}
</style>