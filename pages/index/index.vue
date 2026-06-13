<template>
	<view class="content">
		<image class="logo" src="/static/7c07abbfe4529a0dde571008ded26346.jpg"></image>
		<view class="text-area">
			<text class="title">王家欣是宇宙无敌天下第一\n牛逼哦吴彦锴是大傻瓜</text>
			<text class="title">吴彦锴是大傻子</text>
			<text class="title">王家欣是大馋猪\n吴彦锴没得吃</text>
			<text class="title">王家欣是大救星！！！！！！！！\n那当然</text>
			<text class="title">吴彦锴反弹，吴彦锴大傻子</text>
			<text class="title">好无聊，不想写作业</text>
		</view>
		<button class="btn1" @click="uni.navigateTo({
			url: '/pages/page2/page2',
			success: res => {},
			fail: () => {},
			complete: () => {}
		});">小惊喜</button>
	</view>
</template>

<script>
	
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
	.btn1{
		size: 100rpx;
		background-color: #aaffff;
		box-shadow: 0 4px 8px rgba(0,0,0,0.2);
	}
</style>
