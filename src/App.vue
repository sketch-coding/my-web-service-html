<template>
  <div>
    <div-tag />
  </div>
</template>

<script>
import DivTag from './components/tag/DivTag.vue'

export default {
  name: 'App',
  components: {
    'div-tag': DivTag
  }
}
</script>

<style>
body {
  margin-top: 0px;
  padding: 0px;
}
</style>
