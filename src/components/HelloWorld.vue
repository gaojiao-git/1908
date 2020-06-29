<template>
  <div class="hello">
    <h3>HelloWorld</h3>
    <p>{{ msg }}</p>
    <samp>
      我是谁
      <samp>
        我在哪
        <samp>我在干嘛</samp>
      </samp>
    </samp>
    <h3>123456789</h3>
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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>