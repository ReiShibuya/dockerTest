<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      書き換えてみた
    </p>
    <h3>書き換えてみた2</h3>
    <h3>書き換えてみた3</h3>
    <h3>書き換えてみた4</h3>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

