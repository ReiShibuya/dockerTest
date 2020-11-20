<template>
  <transition appear name="fade">
    <div v-if="show">トランジション</div>
  </transition>
</template>

<script>
  export default {
    data() {
      return {
        show: true
      }
    }
  }
</script>

<style>
  .fade-enter-active, .fade-leave-active {
    transition: opacity .5s;
  }

  .fade-enter, .fade-leave-to {
    opacity: 0;
  }
</style>