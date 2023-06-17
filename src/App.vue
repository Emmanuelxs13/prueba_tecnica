
<template>
  <div id="app">
    <Header />
    <Content />
    <ImagenesApi/>
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Content from "./components/Content.vue"
import ImagenesApi from "./components/ImageApi.vue"

export default {
  name: 'app',
  components: {
    Header,
    Content,
    ImagenesApi
  }
}
</script>

