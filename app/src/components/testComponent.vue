<template>
  <button v-on:click="alertMessage">ボタン</button>
</template>

<script>
export default {
  name: 'alertButton',
  methods: {
    alertMessage: function() {
      alert("Hello world!!!")
    }
  }
}
</script>
