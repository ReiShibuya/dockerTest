<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/star.png">
    <HelloWorld msg="Hello World!"/>
    <AlertBtn />
    <BindingForm />
    <Transitions />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AlertBtn from './components/testComponent'
import BindingForm from './components/testBinding'
import Transitions from './components/testTransition'

export default {
  name: 'App',
  components: {
    HelloWorld,
    AlertBtn,
    BindingForm,
    Transitions
  }
}
</script>

<style>

</style>
