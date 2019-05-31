<template>
	<!--  购物车-->
	<view class="content">
		   <!-- 当前位置 -->
		      	<!-- 地址图片 -->
				<view class="weizhi">
					 <view id="dizhi1">
						<image src="../../static/img/dizhi2.png" class="dizhi2"></image>
						<!-- <text class="dizhi3">上海沙龙小区</text>	 -->
							上海沙龙小区(当前位置)			 
					</view>
					 <!-- 地址名称 -->
					 <!-- <view class="dizhiming">上海沙龙小区(当前位置)</view> -->
				</view>
		     
	   
		      <!-- 购物车 -->
		 <view class="zjzhongtu">
		   <view class="zhongtutimu">华冠-亦庄店</view>
		   <!-- 箭头 -->
		   <view class="jiantou"> > </view>
		   <!-- 横线 -->
		   <view class="hengxian"></view>
		   <view class="zhongtutupian1">
			  <image src="../../static/img/paigu.jpg" class="zhongtutupian2"></image>
		   </view>
		   <!-- 价钱 -->
		      <view class="jiage">￥7.2</view>
		</view>
	</view>
</template>

<script>
	export default {
		// 数据
		data() {
			return {
				
			};
		},
		onLoad() {
		
		},
		// 方法
		methods: {
			
		}
		
	}
</script>

<style>
 @import url("../../static/css/gouwuche.css");	
</style>
