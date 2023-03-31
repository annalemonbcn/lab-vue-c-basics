<template>
  <h2>Iteration 5: Bonus</h2>
  <div class="myDiv" :class="{'bg-lightgreen': original, 'bg-lightblue': !original}">My background color is {{ original ? 'lightgreen' : 'lightblue' }}</div>
  <button @click="_changeBGColor">Click me to change the color</button>
</template>

<script>
export default {
  name: 'IterationFive',
  data() {
    return {
      original: true
    }
  },
  methods: {
    _changeBGColor(){
      this.original = !this.original;
    }
  }
}
</script>

<style scoped>
.myDiv{
  width: 300px;
  height: 300px;
  margin: auto;

  display: flex;
  justify-content: center;
  align-items: center;
}
.bg-lightgreen{
  background-color: lightgreen;
}
.bg-lightblue{
  background-color: lightblue;
}
</style>