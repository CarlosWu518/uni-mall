<template>
	<view>
		<view class="service">
			<view class="serviceItem">
				<image src="../../static/image/icon1.png" mode=""></image>
				魅族官网直供
			</view>
			<view class="serviceItem">
				<image src="../../static/image/icon2.png" mode=""></image>
				满80免运费
			</view>
			<view class="serviceItem">
				<image src="../../static/image/icon3.png" mode=""></image>
				七天无理由退货
			</view>
		</view>
		<view class="showNav">
			<view class="showNavItem">
				<image src="../../static/image/recommend1.png" mode=""></image>
				<text>魅族 16s Pro</text>
			</view>
			<view class="showNavItem">
				<image src="../../static/image/recommend2.png" mode=""></image>
				<text>魅族 16s</text>
			</view>
			<view class="showNavItem">
				<image src="../../static/image/recommend3.jpg" mode=""></image>
				<text>魅族 Note9</text>
			</view>
			<view class="showNavItem">
				<image src="../../static/image/recommend4.jpg" mode=""></image>
				<text>以旧换新</text>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		name: "indexService",
		data() {
			return {

			};
		}
	}
</script>

<style>
	.service {
		padding: 0 40rpx;
		display: flex;
		height: 70rpx;
		background-color: #F7F7F7;
		font-size: 24rpx;
		color: #a3a3a3;
		align-items: center;
		justify-content: space-between;
	}

	.serviceItem {
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.serviceItem image {
		width: 35rpx;
		height: 35rpx;
		margin-right: 10rpx;
	}

	.showNav {
		height: 225rpx;
		display: flex;
		justify-content: space-between;
		padding: 0 40rpx;
		background-color: #FFFFFF
	}

	.showNavItem {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.showNavItem image {
		margin-top: 30rpx;
		width: 100rpx;
		height: 100rpx;
	}

	.showNavItem text {
		display: block;
		font-size: 24rpx;
		color: #000000;
		line-height: 100rpx;
	}
</style>
