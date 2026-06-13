<template>
	<view style="width: 100%; height: 1250rpx;">
		<view style="width: 100%; height: 100%;" class="">
			<view class="chatBox">
				<text class="text">{{chat[currentIndex]?.A}}</text>
			</view>
			<button class="btn" @click="nextChat" >
				<image style="width: 100rpx; height: 100rpx; overflow: hidden;" src="/static/pd-image.png" mode="heightFix"></image>
			</button>
			<view class="chatBox2">
				<text class="text">{{chat[currentIndex]?.B}}</text>
			</view>
		</view>
	</view>
</template>

<script setup>
import { ref } from 'vue';

	const chat = ref([{
		A: '吴彦锴是大傻子',
		B: '才不是，王家欣是大傻子'
	},
	{
		A: '王家欣是大馋猪',
		B: '是的是的'
	},
	{
		A: '王家欣是宇宙无敌天下第一',
		B: '王家欣最厉害！！'
	},
	{
		A: '王家欣真好看',
		B: '是的是的，王家欣是超级大美女'
	},
	{
		A: '完全正确',
		B: '吴彦锴超级大帅B'
	}])
	const currentIndex = ref(0)
	const nextChat = () =>{
		currentIndex.value = (currentIndex.value + 1) % chat.value.length;
	}
</script>

<style>
	.chatBox{
		display: flex;
		justify-content: center;
		align-items: center;
		width: 100%;
		height: 50%;
		background-color: #aaffff;
	}
	.chatBox2{
		display: flex;
		justify-content: center;
		align-items: center;
		width: 100%;
		height: 50%;
		background-color: #ff9395;
	}
	.text{
		font-size: 70rpx;
		margin-left: 50rpx;
		margin-right: 50rpx;
	}
	.btn{
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
		z-index: 10;
		padding: 5px 20px;
		font-size: 30px;
		background-color: #aaff7f; /* 示例颜色 */
		color: #ff575a;
		border: none;
		border-radius: 5px;
		box-shadow: 0 4px 8px rgba(0,0,0,0.2);
		cursor: pointer; /* 鼠标悬停时显示手型 */
		white-space: nowrap; /* 防止按钮文本换行 */
		width: auto; 
		height: auto;
		display: flex;
		justify-content: center;
	}
	
	.btn:active{
		background-color: #9ae270;
	}
</style>
