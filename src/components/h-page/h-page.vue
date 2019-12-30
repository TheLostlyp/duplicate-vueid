<template>
  <view class="h-page">
    <slot></slot>
    <h-dialog></h-dialog>
    <h-toast></h-toast>
  </view>
</template>

<script>
import hToast from '../h-toast/h-toast'
import hDialog from '../h-dialog/h-dialog'
export default {
  components: {
    hToast,
    hDialog,
  },
}

</script>

<style lang="scss">
</style>