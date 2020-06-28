<template>
  <div class="hello">
    <h3>HelloWorld</h3>
    <p>{{ msg }}</p>
    <p>在分支上进行开发：
      <span>master上的代码</span>
    </p>
    <p>在分支上添加代码：
      <span>master上的代码</span>
    </p>
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