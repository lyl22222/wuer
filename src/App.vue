<template>
  <cat></cat>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import cat from './components/cat.vue'

export default defineComponent({
  name: 'App',
  components: {
    cat
  },
})
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
html,body{
  width: 100%;
  height: 100%;
}
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */

}
</style>
