<template>
	<view class="content">
		<!-- 顶部导航 -->
		<MyHeader></MyHeader>
		<!-- 首页轮播 -->
		<IndexSwiper></IndexSwiper>
		<!-- 首页服务和商品导航 -->
		<IndexService></IndexService>
		<!-- 首页广告 -->
		<IndexAD></IndexAD>
		<!-- 楼层1 -->
		<view class="floor">
			<IndexTitle name="智能手机"></IndexTitle>
			<view class="adImg">
				<image src="../../static/image/cate1Ad.jpg" mode=""></image>
			</view>
			<view class="shopList">
				<IndexShopItem></IndexShopItem>
				<IndexShopItem></IndexShopItem>
				<IndexShopItem></IndexShopItem>
				<IndexShopItem></IndexShopItem>
			</view>
		</view>
		<!-- 楼层2 -->
		<view class="floor">
			<IndexTitle name="魅族声乐"></IndexTitle>
			<view class="floorTable">
				<view class="tableItem">
					<image src="../../static/image/cateRecommend1.jpg" mode=""></image>
				</view>
				<view class="tableItem">
					<image src="../../static/image/cateRecommend1.jpg" mode=""></image>
				</view>
				<view class="tableItem">
					<image src="../../static/image/cateRecommend1.jpg" mode=""></image>
				</view>
				<view class="tableItem">
					<image src="../../static/image/cateRecommend4.jpg" mode=""></image>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	import MyHeader from '../../components/index/header.vue'
	import IndexSwiper from '../../components/index/indexSwiper.vue'
	import IndexService from '../../components/index/indexService.vue'
	import IndexAD from '../../components/index/indexAD.vue'
	import IndexTitle from '../../components/index/title.vue'
	import IndexShopItem from '../../components/index/shopItem.vue'
	export default {
		data() {
			return {

			}
		},
		components: {
			MyHeader,
			IndexSwiper,
			IndexService,
			IndexAD,
			IndexTitle,
			IndexShopItem,
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	page {
		background-color: #f4f4f4;
	}

	.adImg {
		width: 100%;
		height: 344rpx;
	}

	.adImg image {
		width: 100%;
		height: 344rpx;
	}

	.shopList {
		display: flex;
		justify-content: space-between;
		flex-wrap: wrap;
	}
	
	.floorTable{
		display: flex;
		justify-content: space-between;
		flex-wrap: wrap;
	}
	
	.floorTable .tableItem{
		width: 50%;
		height: 330rpx;
	}
	
	.floorTable .tableItem image {
		width: 100%;
		height: 100%;
	}
</style>
