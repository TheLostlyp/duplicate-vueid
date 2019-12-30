<template>
  <view>
    <view>form</view>
    <slot></slot>
  </view>
</template>

<script>
export default {
  name: 'h-form',
  provide() {
    return {
      form: this
    }
  },
}
</script>

<style lang="scss">
</style>