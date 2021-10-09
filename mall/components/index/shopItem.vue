<template>
	<view class="shopListItem">
		<image src="../../static/image/p1.png" class="shopImg" mode=""></image>
		<view class="shopTitle">
			魅族 16s Pro
		</view>
		<view class="shopActive">
			<view class="shopActiveLab">
				免息
			</view>
			<view class="shopActiveText">
				<text>4800W AI三摄 屏幕下方屏幕下方</text>
			</view>
		</view>
		<view class="shopPrice">
			￥2699.00
		</view>
	</view>
</template>

<script>
	export default {
		name:"shopItem",
		data() {
			return {
				
			};
		}
	}
</script>

<style>
	.shopListItem {
		width: 370rpx;
		height: 540rpx;
		background-color: #fff;
		margin-top: 10rpx;
	}
	
	.shopListItem .shopImg {
		width: 316rpx;
		height: 316rpx;
		display: block;
		margin: 0 auto 0;
		padding-top: 40rpx;
	}
	
	.shopListItem .shopTitle {
		font-size: 28rpx;
		line-height: 50rpx;
		height: 50rpx;
		text-align: center;
	}
	
	.shopListItem .shopActive {
		height: 40rpx;
		width: 346rpx;
		margin: 0 auto;
		border: 1rpx solid #d9000b;
		display: flex;
	}
	
	.shopActiveLab {
		width: 70rpx;
		background-color: #d9000b;
		font-size: 24rpx;
		height: 40rpx;
		color: #fff;
		line-height: 40rpx;
		text-align: center;
	}
	
	.shopActiveText {
		width: 276rpx;
		font-size: 24rpx;
		height: 40rpx;
		line-height: 40rpx;
		color: #d9000b;
		overflow: hidden;
		/*超出部分隐藏*/
		white-space: nowrap;
		/*不换行*/
		text-overflow: ellipsis;
		/*超出部分文字以...显示*/
		margin-left: 10rpx;
	}
	
	.shopPrice {
		font-size: 28rpx;
		color: #d9000b;
		text-align: center;
		line-height: 80rpx;
	}
</style>
