<template>
  <div>
    <h2>Iteration 3</h2>
    <p v-show="booleanResult">This element only shows if 'booleanResult' is true</p>
    <button @click="changeBooleanResult">Click me to change the 'booleanResult' var</button>  
  </div>
</template>

<script>
export default {
  name: 'IterationThree',
  data() {
    return{
      booleanResult: 'true'
    }
  },
  methods: {
    changeBooleanResult(){
      return this.booleanResult = !this.booleanResult;
    }
  }
}
</script>

<style scoped>

</style>