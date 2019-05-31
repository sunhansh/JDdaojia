<template>
	<view class="content">
		<!-- 表头大食谱图片 -->
		<view class="dashipu1">
			<image src="../../static/img/mian.jpg" class="dashipu2"></image>
		</view>
		
		<!-- 中间内容大食谱图片 -->
		        <!-- 土豆饼 -->
		  <view class="zjdatu">		
			 <view class="datutimu1">这道舌尖上的美味,有个平底锅就能做!</view>
             <view class="datutimu2">我发现,每个热爱工作的人,都有点"职业病"。昨天我跟一个做文案的朋友吃饭。她说,来的路上</view>
			  <view class="datutupian1">
				  <image src="../../static/img/jianbing.jpg" class="datutupian2"></image>
			  </view>			 
		  </view>
		
	</view>
</template>

<script>
	export default {
		data(){
			return{
				title: 'Hello uniapp',
			}					
		},
		onLoad() {
			
		},
		methods:{
			
		}
	}
</script>

<style>
@import url("../../static/css/tuijian.css");	
</style>
