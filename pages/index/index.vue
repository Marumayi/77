<template>
	<view class="content">
		<image class="logo" src="/static/7c07abbfe4529a0dde571008ded26346.jpg"></image>
		<view class="miss">
			<text class="longing">不知道这些话我要写在哪里，不表达出
			来又好难受，突然想起来我们一起编辑过这个项目，你大概率不会
			再打开了，干脆我写这里吧。\n
			你看到这段话的时候不知道我们关系是变好了还是更坏了,现在看到
			前面那些我们一起写的内容还挺伤感的。\n
			从我们开始有频繁交流到现在已经快3个月了，你说我可能只是因
			为聊天太多产生了喜欢的错觉，我也这样子怀疑过，但是现在我发现我
			还是喜欢你，我讨厌不起来。\n
			我也不清楚从什么时候开始，我好像感觉到你对我的好感在慢慢消失，
			发的文字语气越来越冷漠，有时候甚至有些敷衍。你好像有点讨厌我
			了。直到最近，我发现你的瓦小号把我好友删了（我的瓦好友就几个，
			一眼就能看到），我去问了你，你说号借别人玩了，之后便没再多说。
			按我的思路，如果我的朋友突然给我说我把他删了，我会上号看看然
			后和他说到底怎么回事的。我感觉你在骗我，我有点生气，但伤心更多。\n
			我后面回想起来，我感觉好像是我一直在打扰你。但是我好喜欢你啊，
			我一直在想我会不会很打扰你，但是我又每次都忍不住给你发消息。接着
			我就慢慢发现你越来越冷漠。也可能是我太敏感了吧。但这种看着自己
			喜欢的人慢慢地讨厌自己的感觉，真的好难受。最难受的是，我实际上没
			有资格难受，因为我们还只是朋友。我有点不知道要怎么面对你了。\n
			王家欣，我真的好喜欢你，我该怎么办啊。\n
			上面这些话对于普通朋友来说有点超纲了，我并没有责怪你的意思，就是
			憋着难受，所以我就写这里了。要是你已经看到了，你可以给我发一个
			“我看到了”的消息吗？emm。。如果你还不讨厌我，就在这条消息后面再
			发一个你喜欢的小表情吧。
			</text>
		</view>
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
		margin-top: 10rpx;
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
	.miss{
		background-color: #aaffff;
		border-radius: 30rpx;
		margin: 10rpx;
		padding: 10px;
		width: 80%
	}
	.longing{
		margin: 10rpx;
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
