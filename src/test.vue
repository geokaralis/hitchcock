<template>
<div>
  <h2>Hello from {{text}}</h2>
</div>

</template>

<script>
export default {
  name: 'test',
  data () {
    return {
       text: ''
    }
  }
}
</script>

<style scoped>
div {
  width: 70%;
  height: 100%;
  background: #1e1e1e;
  border-left: 2px solid #000;
}
h2 {
  color: #fff;
}
</style>

