<template>
	<view class="content">
		<view>
				<!-- 点击只变颜色 -->
		   <view class="anniou">	   
			  <button class="month" :style={background:bgcolor2} @click="fn3('month')">月</button>				  
			  <button class="day" :style={background:bgcolor1} @click="fn3('day')">日</button>
		   </view>
	   </view>
		
	</view>
</template>

<script>
	export default {
		data: {
			// 点击只变颜色
			bgcolor1:'white',
			bgcolor2:'silver'
			
		},
		onLoad() {
			
		},
		methods:{
			  fn3(type){
					 if (type=='day') {
						this.bgcolor1='white';
						this.bgcolor2='silver';			
					 } else{
						this.bgcolor1='silver';
						this.bgcolor2='white';
					 }
			 },
		}
	}
</script>

<style>
	.content {
		margin-top: 50upx;
		text-align: center;
		height: 400upx;
	}

	.title {
		font-size: 36upx;
	}
</style>
