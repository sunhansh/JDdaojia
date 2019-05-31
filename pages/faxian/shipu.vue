<template>
	<view class="content">
		<!-- 表头大食谱图片 -->
		<view class="dashipu1">
			<image src="../../static/img/dashipu1.jpg" class="dashipu2"></image>
		</view>
		<!-- 输入框 搜食材 -->
		   <!-- 放大镜 -->
		   <view class="soucai1">
			   <view class="fangdajing1">
				    <image src="../../static/img/fangdajing.png" class="fangdajing2"></image>
			   </view>			  
			   <input placeholder="搜索菜名 食材" class="soucai2"/>
		   </view>		
		

			 <!-- 功能小图 -->
			 
			  <view class="gnxioatu0">
				 <view class="gnxioatu2"></image></view>
				 <view class="gnxioatu1">家常菜</view>		    	 
			  </view>
			  <!-- 肉类食谱 -->
			  <view class="gnxioatu0">
				 <view class="gnxioatu2"></image></view>
				 <view class="gnxioatu1">肉类食谱</view>		    	 
			  </view>
			   <!-- 水产海鲜 -->
			  <view class="gnxioatu0">
				 <view class="gnxioatu2"></image></view>
				 <view class="gnxioatu1">水产海鲜</view>		    	 
			  </view>
		 <!-- 蔬菜食谱 -->
			  <view class="gnxioatu0">
				 <view class="gnxioatu2"></image></view>
				 <view class="gnxioatu1">蔬菜食谱</view>		    	 
			  </view>
	   <!-- 母婴食谱 -->
			<view class="gnxioatu0">
				 <view class="gnxioatu2"></image></view>
				 <view class="gnxioatu1">母婴食谱</view>		    	 
			</view>  
        <!-- 蛋奶制品 -->
			<view class="gnxioatu0">
				 <view class="gnxioatu2"></image></view>
				 <view class="gnxioatu1">蛋奶制品</view>		    	 
			</view> 			
		  <!-- 烘焙 -->
		<view class="gnxioatu0">
			 <view class="gnxioatu2"></image></view>
			 <view class="gnxioatu1">烘焙</view>		    	 
		</view> 
     <!-- 食疗养生 -->
		<view class="gnxioatu0">
			 <view class="gnxioatu2"></image></view>
			 <view class="gnxioatu1">食疗养生</view>		    	 
		</view>
	<!-- 减肥餐 -->
		<view class="gnxioatu0">
			 <view class="gnxioatu2"></image></view>
			 <view class="gnxioatu1">减肥餐</view>		    	 
		</view>
		<!-- 米面杂粮 -->
		<view class="gnxioatu0">
			 <view class="gnxioatu2"></image></view>
			 <view class="gnxioatu1">米面杂粮</view>		    	 
		</view>
		         <!-- 热门食谱 -->
		   <view class="datutimu">热门食谱</view>	
		<!-- 中间内容大食谱图片 -->
		        <!-- 土豆饼 -->
		  <view class="zjdatu">			 
			  <view class="datutupian1">
				  <image src="../../static/img/bing.jpg" class="datutupian2"></image>
			  </view>
			   <view class="datutimu">土豆饼</view>
		  </view>
		   <!-- 黄焖鸡 -->
		     <view class="zjdatu">			   
			   <view class="datutupian1">
				  <image src="../../static/img/tudoubing.jpg" class="datutupian2"></image>
			   </view>
			    <view class="datutimu">黄焖鸡</view>
		    </view>
			
			<!-- 中间内容 中形食谱图片 -->
			         <!-- 简单美味糖醋排骨 -->
			  <view class="zjzhongtu">
			    <view class="zhongtutimu">简单美味糖醋排骨</view>
			    <view class="zhongtutupian1">
			 	  <image src="../../static/img/paigu.jpg" class="zhongtutupian2"></image>
			    </view>
			 </view>
			          <!-- 什锦西兰花 -->
			  <view class="zjzhongtu">
			    <view class="zhongtutimu">什锦西兰花</view>
			    <view class="zhongtutupian1">
			 	  <image src="../../static/img/xilanhua.jpg" class="zhongtutupian2"></image>
			    </view>
			 </view>
			          <!-- 米粉 -->
			  <view class="zjzhongtu">
			    <view class="zhongtutimu">米粉</view>
			    <view class="zhongtutupian1">
			 	  <image src="../../static/img/mifen.jpg" class="zhongtutupian2"></image>
			    </view>
			 </view>
			 
	     <!-- 中间内下方容大食谱图片 -->
	             <!-- 红烧狮子头 -->
	       <view class="zjdatu">			 
	     	  <view class="datutupian1">
	     		  <image src="../../static/img/shizitou.jpg" class="datutupian2"></image>
	     	  </view>
	     	   <view class="datutimu">红烧狮子头</view>
	       </view>
		          <!-- 剁椒鱼头 -->
		   <view class="zjdatu">			 
			  <view class="datutupian1">
				  <image src="../../static/img/yutou.jpg" class="datutupian2"></image>
			  </view>
			   <view class="datutimu">剁椒鱼头</view>
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
@import url("../../static/css/shipu.css");	
</style>
