<template>
  <div>
    <button @click="increment">Increment +1</button>
  </div>
</template>

<script>
import { increment } from '../vuex/actions'

export default {
  name: 'increment',
  vuex: {
    actions: {
      increment
    }
  }
}
</script>

<style lang="css" scoped>
</style>
