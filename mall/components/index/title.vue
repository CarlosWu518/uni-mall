<template>
	<view class="floorTitle">
		<view class="title">
			{{name}}
		</view>
		<view class="line">

		</view>
	</view>
</template>

<script>
	export default {
		name: "title",
		props:['name'],
		data() {
			return {

			};
		}
	}
</script>

<style>
	.floorTitle {
		height: 180rpx;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.floorTitle .title {
		font-size: 32rpx;
		color: #000000;
		font-weight: bold;
		margin-bottom: 20rpx;
	}

	.floorTitle .line {
		height: 6rpx;
		width: 44rpx;
		background-color: #07baf2;
	}
</style>
