<template>
  <Layout>
    <Content><TaskQuadrants msg="Welcome to Your Vue.js App"/></Content>
  </Layout>
</template>

<script>
import TaskQuadrants from './components/TaskQuadrants.vue'
import {Layout , Content } from 'tdesign-vue-next'

export default {
  name: 'App',
  components: {
    Layout,  Content,
    TaskQuadrants
  }
}
</script>

<style>
layout {
 height: 100px;
}
</style>
