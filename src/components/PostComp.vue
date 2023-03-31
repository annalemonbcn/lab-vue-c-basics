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
    }
  }
}
</script>

<style>
.post{
  margin-top: 30px;
}
</style>