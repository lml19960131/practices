<template>
  <div class="hello">
    <div v-html="message"></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      message: '<h1>连明亮</h1>'
    }
  }
}
</script>

<style>
  .hello{
    font-family: Arial,sans-serif;
    font-size: 28px;
    color: deepskyblue;

  }
</style>

