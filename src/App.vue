<template>
  <div id="app">
    <TopBar></TopBar>
    <Content></Content>
  </div>
</template>

<script>
import TopBar from './components/TopBar'
import Content from './components/Content'

export default {
  components: {
    TopBar,
    Content
  }
}
</script>
