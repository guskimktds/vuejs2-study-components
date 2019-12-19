<template>
  <div>
    <h1>List of Raccoons</h1>
    <ul>
      <li v-for="raccoon in raccoons">{{ raccoon }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data () {
    return {
      raccoons: ['Kim','Oho','Lee']
    }
  }
}
</script>

<style scoped>
h1 {
  color: green;
}
</style>
