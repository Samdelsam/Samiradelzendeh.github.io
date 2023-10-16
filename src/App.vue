<template>
  <HeaderPor/>
  <img alt="Vue logo" src="./assets/sam.jpeg">
  <HelloWorld/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HeaderPor from "@/components/HeaderPor.vue";
export default {
  name: 'App',
  components: {
    HelloWorld,
    HeaderPor
  }
}
</script>

<style>
#app {
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

img{
  max-width: 80%;
  max-height: 60%;
  margin-top:30px;
}
</style>
