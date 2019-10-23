<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class SampleMain extends Vue {
  message = 'test'
}
</script>
<template lang="pug">
  .w-100.bg-black.text-white.active
    | Hello world! {{message}}
</template>
<style lang="stylus" scoped>
.active
  height 20vh
</style>
