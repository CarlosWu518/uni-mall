<template>
	<view>
		<swiper :indicator-dots="true" :autoplay="true" :interval="3000" :duration="1000" indicator-color="#7d7c82"
			indicator-active-color="#fefefe">
			<swiper-item>
				<view class="swiper-item">
					<image src="../../static/image/banner1.jpg" mode=""></image>
				</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item">
					<image src="../../static/image/banner2.jpg" mode=""></image>
				</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item">
					<image src="../../static/image/banner3.jpg" mode=""></image>
				</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item">
					<image src="../../static/image/banner4.jpg" mode=""></image>
				</view>
			</swiper-item>
		</swiper>
	</view>
</template>

<script>
	export default {
		name: "indexSwiper",
		data() {
			return {

			};
		}
	}
</script>

<style>
	uni-swiper {
		width: 100%;
		height: 390rpx;
	}

	uni-swiper image {
		width: 100%;
		height: 390rpx;
	}
</style>
