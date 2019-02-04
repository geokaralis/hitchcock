<template>
  <div class="titlebar">
    <!-- <h1>{{title}}</h1> -->
  </div>
</template>

<script>
export default {
  name: 'titlebar',
  props: ['title']
}
</script>

<style scoped>
.titlebar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 22px;
  /* background: linear-gradient(to top, #444342 0%, #51504e 100%); */
  color: rgba(255, 255, 255, 0.8);
  display: flex;
  align-items: center;
  justify-content: center;
  -webkit-app-region:drag;
}

.titlebar h1 {
  margin: 0;
  font-size: 13px;
  font-weight: normal;
}
</style>


