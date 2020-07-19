<template>
  <div id="hello-vue" class="demo">
    {{ message }}
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello Vue!!',
    }
  },
  mounted() {
    window.HelloVueVm = this
  }
}
</script>

<style scoped>
.demo {
  font-family: sans-serif;
  border: 1px solid #eee;
  border-radius: 2px;
  padding: 20px 30px;
  margin-top: 1em;
  margin-bottom: 40px;
  user-select: none;
  overflow-x: auto;
}
</style>