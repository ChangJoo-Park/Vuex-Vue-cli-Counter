<template>
  <div>
    <button @click="decrement">Decrement -1</button>
  </div>
</template>

<script>
import { decrement } from '../vuex/actions'

export default {
  name: 'decrement',
  vuex: {
    actions: {
      decrement
    }
  }
}
</script>

<style lang="css" scoped>
</style>
