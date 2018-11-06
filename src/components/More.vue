<template>
  <div class="component">
    <h2>{{ message }}</h2>
    <p>Except to <router-link to="/">Go on back to the beginning</router-link></p>
  </div>
</template>


<script>
  export default {
    data () {
      return {
        message: 'There is not much else to do here.'
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