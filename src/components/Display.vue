<template>
  <div>
    <h3>Count is {{ counterValue }}</h3>
  </div>
</template>

<script>
import { getCount } from '../vuex/getters'

export default {
  name: 'display',
  vuex: {
    getters: {
      //  No getCount()
      counterValue: getCount
    }
  }
}
</script>

<style lang="css" scoped>
</style>
