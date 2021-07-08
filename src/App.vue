<template>
    <HelloWorld msg=""/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
@import url(https://fonts.googleapis.com/css?family=Anonymous+Pro);

body{
  font-family: 'Anonymous Pro', monospace; 
  background-image: url("https://appleinformed.files.wordpress.com/2021/06/macosmontereywallpaper.jpg");
}
</style>
