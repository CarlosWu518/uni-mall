<template>
	<view>
		<view class="status"></view>
		<view class="header">
			<view class="navbar">
				<view class="search">
					<image src="../../static/image/search.png" mode=""></image>
				</view>
				<view class="logo">
					<image src="../../static/image/logo.png" mode=""></image>
				</view>
				<view class="cart">
					<image src="../../static/image/trolley.png" mode=""></image>
				</view>
			</view>
			<view class="menuTap">
				<view class="menuTapItem menuActive">
					推荐
				</view>
				<view class="menuTapItem">
					手机
				</view>
				<view class="menuTapItem">
					声学
				</view>
				<view class="menuTapItem">
					配件
				</view>
				<view class="menuTapItem">
					生活
				</view>
			</view>
		</view>
		<view class="headerEmpty">
		</view>
	</view>
</template>

<script>
	export default {
		name:"header",
		data() {
			return {
				
			};
		}
	}
</script>

<style>
	.status {
		height: var(--status-bar-height);
		width: 100%;
		position: fixed;
		top: 0;
		z-index: 9;
	}
	
	.header {
		width: 100%;
		height: 180rpx;
		position: fixed;
		background-color: #fff;
		z-index: 9;
		top: var(--status-bar-height);
	}
	
	.headerEmpty {
		height: 180rpx;
	}
	
	.navbar {
		height: 110rpx;
		display: flex;
		flex-direction: row;
		margin: 0 20rpx;
		justify-content: space-between;
		align-items: center;
	}
	
	.navbar .search image {
		width: 30rpx;
		height: 30rpx;
	}
	
	.navbar .logo image {
		width: 140rpx;
		height: 30rpx;
	}
	
	.navbar .cart image {
		width: 30rpx;
		height: 30rpx;
	}
	
	.menuTap {
		height: 70rpx;
		display: flex;
		flex-direction: row;
		margin: 0 20rpx;
		justify-content: space-between;
	}
	
	.menuTap .menuTapItem {
		font-size: 28rpx;
		width: 60rpx;
		height: 55rpx;
		text-align: center;
		color: #000000;
	}
	
	.menuTap .menuActive {
		color: #0bbbef;
		border-bottom: 1rpx #0bbbef solid;
	}
</style>
