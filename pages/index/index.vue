<template>
	<view class="content">
		<image class="logo" src="/static/7c07abbfe4529a0dde571008ded26346.jpg"></image>
		<view class="text-area">
			<text class="title">王家欣是宇宙无敌天下第一\n牛逼哦吴彦锴是大傻瓜</text>
			<text class="title">王家欣是大傻子</text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
