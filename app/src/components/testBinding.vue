<template>
  <div>
    <input type="text" v-model="msg">
    {{ msg }}
  </div>
</template>

<script>
  export default {
    data() {
      return {
        msg: "test"
      }
    }
  }
</script>