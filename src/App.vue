<template>
  <div>
    <h8k-navbar v-bind:header="title"></h8k-navbar>
    <h1>Hello World</h1>
  </div>
</template>

<script>

export default {
  components: {

  },
  data() {
    return {
      title: 'Color Picker',
    }
  }
}
</script>

<style lang="scss">
@import '../node_modules/h8k-design/dist/index.css';
</style>
