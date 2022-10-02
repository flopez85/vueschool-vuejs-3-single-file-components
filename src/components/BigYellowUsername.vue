<template>
  <p class="username">{{ username }}</p>
</template>

<script>
export default {
  props: {
    username: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="css">
  .username {
    font-size: 50pt;
    color: #42b983;
  }
</style>
