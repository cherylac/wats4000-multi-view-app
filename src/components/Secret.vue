<template>
  <div class="component">
    <h2>{{ message }}</h2>
    <p>Go back to <router-link to="/survey">survey.</router-link></p>
    <p>To Start Over <router-link to="/">Click Here</router-link></p>
    <p>Want more? <router-link to="/more">Click Here</router-link></p>
  </div>
</template>


<script>
  export default {
    data () {
      return {
        message: 'Mind your syntax and keep your code clean!'
      }
    }
  }
</script>

<style scoped>
  .component {
    background: #e8e8e8;
    min-height: 400px;
  }
</style>