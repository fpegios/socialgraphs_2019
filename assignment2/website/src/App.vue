<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'app'
}
</script>

<style>

html, body, #app {
  height: 100%;
}

.tabs .card-header {
  position: fixed!important;
}

.tab-content {
  margin-left: 200px;
}

</style>
