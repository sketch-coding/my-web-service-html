<template>
  <div>
    <!-- <div-tag /> -->
    <text-tag />
  </div>
</template>

<script>
import DivTag from './components/tag/DivTag.vue'
import TextTag from './components/tag/TextTag'

export default {
  name: 'App',
  components: {
    'div-tag': DivTag,
    'text-tag': TextTag
  }
}
</script>

<style>
body {
  margin-top: 0px;
  padding: 0px;
}
</style>
