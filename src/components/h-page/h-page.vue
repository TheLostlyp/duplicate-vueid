<template>
  <view class="h-page">
    <slot></slot>
    <h-dialog></h-dialog>
    <h-navbar></h-navbar>
    <h-toast></h-toast>
  </view>
</template>

<script>
import hToast from '../h-toast/h-toast'
import hDialog from '../h-dialog/h-dialog'
import hNavbar from '../h-navbar/h-navbar'
export default {
  components: {
    hToast,
    hDialog,
    hNavbar,
  },
}

</script>

<style lang="scss">
</style>