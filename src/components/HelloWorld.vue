<template>
  <div class="hello">
    <h3>HelloWorld</h3>
    <h1>{{ msg }}</h1>
    <samp>
      我是谁
      <samp>
        我在哪
        <samp>我在干嘛</samp>
      </samp>
    </samp>
    <p>在master上修改代码</p>
    <p>在dev分支上修改</p>
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