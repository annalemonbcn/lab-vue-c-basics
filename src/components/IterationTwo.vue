<template>
  <div>
    <h2>Iteration 2</h2>
    <p>Easy mathematical operation:</p>
    <p>{{ 2+2 }}</p>
  </div>
  <div>
    <p>Print a string:</p>
    <p>{{ returnString() }}</p>
  </div>
</template>

<script>
export default {
  name: 'IterationTwo',
  data() {
    return{
      myString: 'Hi, this is a test string'
    }
  },
  methods: {
    returnString(){
      return this.myString;
    }
  }
}
</script>

<style scoped>

</style>