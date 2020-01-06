<template>
<h-page>
  <view class="content">
    <image class="logo" src="/static/logo.png"></image>
    <view>
      <text class="title">{{title}}</text>
    </view>
    <h-form>
      <h-test>
        <h-form-item></h-form-item>
      </h-test>
    </h-form>
  </view>
</h-page>
</template>

<script>
import hPage from '../../components/h-page/h-page'
import hTest from '../../components/h-form/h-test'
import hForm from '../../components/h-form/h-form'
import hFormItem from '../../components/h-form/h-form-item'
	export default {
    components: {
      hPage,
      hForm,
      hFormItem,
      hTest,
    },
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {
      console.log(this)
		},
		methods: {

		}
	}
</script>

<style>
	.content {
		text-align: center;
		height: 400upx;
	}

	.logo {
		height: 200upx;
		width: 200upx;
		margin-top: 200upx;
	}

	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
</style>
