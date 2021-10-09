<template>
	<view>
		<view class="indexAD">
			<view class="indexADLeft">
				<image src="../../static/image/ad1.jpg" mode=""></image>
			</view>
			<view class="indexADReft">
				<view class="indexADReftItem">
					<image src="../../static/image/ad2.jpg" mode=""></image>
				</view>
				<view class="indexADReftItem">
					<image src="../../static/image/ad3.png" mode=""></image>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		name:"indexAD",
		data() {
			return {
				
			};
		}
	}
</script>

<style>
	.indexAD{
		display: flex;
		border-top: 20rpx solid #f4f4f4;
	}
	.indexAD image{
		width: 100%;
		height: 100%;
	}
	.indexADLeft{
		width: 50%;
		height: 520rpx;
	}
	.indexADReft{
		width: 50%;
	}
	.indexADReftItem{
		height: 260rpx;
	}
</style>
