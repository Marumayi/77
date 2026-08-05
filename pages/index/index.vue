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
			只不过，我现在有点感觉你在慢慢变讨厌我，你发消息的语气越来越冷漠，
			游戏好像也不太愿意和我一起玩的样子，那天我找你玩游戏，你说你约了
			五排，后面我晚上睡不着想上线玩一会，我好奇去点开你的主页（这里我
			先说声抱歉，这有些冒犯，发现这件事后我真的很伤心），你并没有五排，
			你先玩了三排后面又去玩双排，最后还玩了单挑。你可能会说你和朋友玩
			我不好加进去，但我之前也跟你一起和他们打过游戏呀。再后面，我发现
			你的瓦小号把我好友删了（我的瓦好友就几个，一眼就能看到），我去问
			了你，你说号借别人玩了，之后便没再多说。按我的思路，如果我的朋友
			突然给我说我把他删了，我会上号看看然后和他说到底怎么回事的。我感
			觉你在骗我，我有点生气，但伤心更多。\n
			我一直在想我会不会很打扰你，但是我又每次都忍不住给你发消息。也可
			能是我太敏感了吧。但这种看着自己喜欢的人慢慢地讨厌自己的感觉，真
			的好难受。最难受的是，我实际上没有资格难受，因为我们还只是朋友。
			我有点不知道要怎么面对你了。\n
			于是我想这几天我自己冷静一下吧，先不和你发微信了，我怕我现在的心
			情去和你交流会把关系搞得更糟糕，我怕你会更讨厌我。\n
			王家欣，我真的好喜欢你，不要讨厌我好不好T_T。\n
			上面这些话对于普通朋友来说有点超纲了，我并没有责怪你的意思，就是
			憋着难受，所以我就写这里了，你大概率也不会看到这些。emm。。要是
			你已经看到了，你可以给我发一个“我看到了”的消息吗？如果你还不讨厌
			我，就在这条消息后面再发一个你喜欢的小表情吧。
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
