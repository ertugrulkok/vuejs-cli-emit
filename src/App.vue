<template>
<div class="container">
    <HelloWorld />
</div>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {

  data() {
return{

}
  },
  name: 'App',
  components: {
    HelloWorld
  },

}
</script>

<style>
.container {
  font-family: Avenir, Helvetica, Arial, sans-serif;
   text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
  justify-content:space-around;
  flex-direction: row;
}
</style>
