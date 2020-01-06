<template>
  <view>
    <view>h-test</view>
    <slot></slot>
  </view>
</template>

<script>
export default {
  name: 'h-test',
  mounted () {
    console.log(this)
  },
}
</script>

<style lang="scss">
</style>