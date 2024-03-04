<template>
  <div id="app">
    <div id="possible-new-content">

    </div>
    <div id="other-content">
      <img alt="Vue logo" src="./assets/logo.png">
      <HelloWorld msg="Welcome to Your Vue.js Apperinomino"/>
    </div>
    <div id="task-overview">
      <tasks />
    </div>

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Tasks from "@/components/task-overview.vue";

export default {
  name: 'App',
  components: {
    Tasks,
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background: darkslategray;
  margin-top: 60px;
  display: flex;
  width: 100%;
}

#possible-new-content {
  flex: 1;
  padding: 20px;
}

#task-overview {
  flex: 1;
  padding: 20px;
}

#other-content {
  flex: 1;
  padding: 20px;
}
</style>
