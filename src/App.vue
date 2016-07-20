<template>
  <div id="app">
    <Display></Display>
    <Increment></Increment>
    <Decrement></Decrement>
  </div>
</template>

<script>
import Display from './components/Display'
import Increment from './components/Increment'
import Decrement from './components/Decrement'

export default {
  components: {
    Display,
    Increment,
    Decrement
  }
}
</script>

<style>
html {
  height: 100%;
}

body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}

#app {
  color: #2c3e50;
  margin-top: -100px;
  max-width: 600px;
  font-family: Source Sans Pro, Helvetica, sans-serif;
  text-align: center;
}

#app a {
  color: #42b983;
  text-decoration: none;
}

.logo {
  width: 100px;
  height: 100px
}
</style>
