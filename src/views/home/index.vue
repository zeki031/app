<template>
  <h1>hello Home</h1>
</template>

<script lang="ts" setup>
import { useStore } from '../../store/index'

const store = useStore()
console.log(store.state.count) // 0

</script>

<style lang="scss" scoped>
</style>
