<template>
	<!-- 首页 -->
	<view class="content">
		<!-- 头部 1-->
		<view class="toulv1">
			<!-- 地址图片 -->
			<view id="dizhi1">
				<image src="../../static/img/dizhi2.png" class="dizhi2"></image>
				<!-- <text class="dizhi3">上海沙龙小区</text>	 -->				 
			</view>
			 <!-- 地址名称 -->
			   <view class="dizhiming">上海沙龙小区</view>
			 
			<!-- 分类图片 -->
		<view id="fenlei1">
			<image src="../../static/img/fenlei.png" class="fenlei2"></image>
		</view>				
	</view>
						
		<!-- 头部 2 -->
		<view class="toulv2">
			<!-- 搜索框 -->
			   <!-- 放大镜 -->
			<view class="soucai1">
			   <view class="fangdajing1">
					<image src="../../static/img/fangdajing.png" class="fangdajing2"></image>
			   </view>			  
			   <input placeholder="酸奶" class="soucai2"/>
			</view>	
			
			
			<!-- 产品名称 -->
			<view class="chanpin">
				<ul v-for="obj in arr" :key="obj">
					<li>{{obj}}</li>
				</ul>
			</view>
			<!-- 图片 -->
			<view class="tupian1">
				<image src="../../static/img/shangjiari.jpg" class="tupian2"></image>
			</view>	
					
			
				 <!-- 功能小图 -->
				 
				  <view class="gnxioatu0">
					 <view class="gnxioatu2">超</image></view>
				  	 <view class="gnxioatu1">超级便利</view>		    	 
				  </view>
				  <!-- 生鲜果蔬 -->
				  <view class="gnxioatu0">
				  	 <view class="gnxioatu2">生</image></view>
				  	 <view class="gnxioatu1">生鲜果蔬</view>		    	 
				  </view>
				   <!-- 烘焙蛋糕 -->
				  <view class="gnxioatu0">
				  	 <view class="gnxioatu2">糕</image></view>
				  	 <view class="gnxioatu1">烘焙蛋糕</view>		    	 
				  </view>
				     <!-- 鲜花绿植 -->
				  <view class="gnxioatu0">
				  	 <view class="gnxioatu2">花</image></view>
				  	 <view class="gnxioatu1">鲜花绿植</view>		    	 
				  </view>
				 <!-- 医药健康 -->
				<view class="gnxioatu0">
					 <view class="gnxioatu2">医</image></view>
					 <view class="gnxioatu1">医药健康</view>		    	 
				</view>  
		     <!-- 家居时尚 -->
				<view class="gnxioatu0">
					 <view class="gnxioatu2">家</image></view>
					 <view class="gnxioatu1">家居时尚</view>		    	 
				</view> 			
			  <!-- 限时抢券 -->
			<view class="gnxioatu0">
				 <view class="gnxioatu2">抢</image></view>
				 <view class="gnxioatu1">限时抢券</view>		    	 
			</view> 
		 <!-- 签到 -->
			<view class="gnxioatu0">
				 <view class="gnxioatu2">签</image></view>
				 <view class="gnxioatu1">签到</view>		    	 
			</view>
			<!-- 邀请有奖 -->
			<view class="gnxioatu0">
				 <view class="gnxioatu2">邀</image></view>
				 <view class="gnxioatu1">邀请有奖</view>		    	 
			</view>
			<!-- 0元抽奖 -->
			<view class="gnxioatu0">
				 <view class="gnxioatu2">抽</image></view>
				 <view class="gnxioatu1">0元抽奖</view>		    	 
			</view>
		<!-- 新人福利 -->	
			<view class="xinrenfuli1">
				<image src="../../static/img/xinrenfuli.jpg" class="xinrenfuli2"></image>
			</view>
		<!-- 轮播图 -->
		 <!-- 轮播图 -->
				 <!-- <view class="luenbo1"><img :src="imgSrc" class="luenbo2" /></view> -->
			  <view class="uni-padding-wrap">
		           <view class="page-section swiper">
		               <view class="page-section-spacing">
		            <swiper class="swiper" :circular="circular" :indicator-dots="indicatorDots" :autoplay="autoplay" :interval="interval" :duration="duration">
					   <swiper-item>
						   <view class="swiper-item uni-bg-red">
								<image src="../../static/img/luenbo01.jpg" class="luenbotu"></image>
							</view>
					   </swiper-item>
					   <swiper-item>
						   <view class="swiper-item uni-bg-green">
								<image src="../../static/img/luenbo02.jpg" class="luenbotu"></image>
							</view>
					   </swiper-item>
				   <swiper-item>
					   <view class="swiper-item uni-bg-green">
						  <image src="../../static/img/luenbo03.jpg" class="luenbotu"></image>
						</view>
				  </swiper-item>
				 <swiper-item>
					  <view class="swiper-item uni-bg-green">
						<image src="../../static/img/luenbo04.jpg" class="luenbotu"></image>
					 </view>
				  </swiper-item>
				   <swiper-item>
					  <view class="swiper-item uni-bg-green">
						<image src="../../static/img/luenbo05.jpg" class="luenbotu"></image>
					  </view>
				   </swiper-item>
				    <swiper-item>
						  <view class="swiper-item uni-bg-green">
							<image src="../../static/img/luenbo06.jpg" class="luenbotu"></image>
						 </view>
				    </swiper-item>
					
				   </swiper>							
			   </view>
		   </view>
	   </view>
		   
		<!-- 活动 -->
		    <!-- 运费减免日 -->
			<view class="huodong">
				<view class="biaoti">运费减免日</view>
				<!-- 小标题 -->
				<view class="xiaobiaoti1">最高免4元</view>
				<!-- 红色小标题 -->
				<view class="hongbiaoti">天天优惠></view>
				<!-- 活动图片 -->
				 <view class="hongdongtu1">
					 <image src="../../static/img/kele.jpg" class="hongdongtu2"></image>
				 </view>
			</view>
			<!-- 1元逛菜市场 -->
			<view class="huodong">
				<view class="biaoti">1元逛菜市场</view>
				<!-- 小标题 -->
				<view class="xiaobiaoti2">领券减15+运费减免</view>
				<!-- 红色小标题 -->
				<view class="hongbiaoti">立即抢购></view>
				<!-- 活动图片 -->
				 <view class="hongdongtu1">
					 <image src="../../static/img/kele.jpg" class="hongdongtu2"></image>
				 </view>
			</view>
	<!-- 产品 -->
		  <!-- 全场减18 -->
		  	 <view class="chanpin0">
		  		<view class="chanpin1">全场减18 </view>
		  		 <view class="chanpin2">荔枝7.9/斤</view>		    	 
		  	</view>
		 <!-- 京东快药 -->
			 <view class="chanpin0">
				<view class="chanpin1">京东快药</view>
				 <view class="chanpin2">满39减15</view>		    	 
			</view>
	 <!-- 活力7鲜 -->
		 <view class="chanpin0">
			<view class="chanpin1">活力7鲜 </view>
			<view class="chanpin2">最高减8元</view>		    	 
		</view>
		 <!--水果日 -->
		 <view class="chanpin0">
			<view class="chanpin1">水果日</view>
			<view class="chanpin2">樱桃19.9起</view>		    	 
		</view>
		   
		<!-- 产品图片 -->
		   <!-- 华冠 产品图片-->
		    <view class="chanpintu1">
				<image src="../../static/img/huaguan.jpg" class="chanpintu2"></image>
			</view>
			<!-- 京东快药 产品图片-->
			 <view class="chanpintu1">
				<image src="../../static/img/yaopin.jpg" class="chanpintu2"></image>
			</view>
			<!-- 活力7鲜  产品图片-->
			 <view class="chanpintu1">
				<image src="../../static/img/qixian.jpg" class="chanpintu2"></image>
			</view>
			<!-- 水果日  产品图片-->
			 <view class="chanpintu1">
				<image src="../../static/img/yingtao.jpg" class="chanpintu2"></image>
			</view>
			
			
			<!-- 轮播图 -->
					 <!-- 轮播图 -->
							 <!-- <view class="luenbo1"><img :src="imgSrc" class="luenbo2" /></view> -->
			  <view class="uni-padding-wrap">
				   <view class="page-section swiper">
					   <view class="page-section-spacing">
					<swiper class="swiper" :circular="circular" :indicator-dots="indicatorDots" :autoplay="autoplay" :interval="interval" :duration="duration">
					   <swiper-item>
						   <view class="swiper-item uni-bg-red">
								<image src="../../static/img/xialunenbo1.jpg" class="luenbotu"></image>
							</view>
					   </swiper-item>
					   <swiper-item>
						   <view class="swiper-item uni-bg-green">
								<image src="../../static/img/xialunenbo2.jpg" class="luenbotu"></image>
							</view>
					   </swiper-item>
				    <swiper-item>
					   <view class="swiper-item uni-bg-green">
						  <image src="../../static/img/xialunenbo3.jpg" class="luenbotu"></image>
						</view>
				    </swiper-item>
					
				  </swiper>							
			  </view>
		   </view>
	 </view>
			
			
		
		</view>
	   
		  
	
	</view>
</template>

<script>
	export default {
		// 数据
		data() {
			return {
				arr:['妇炎洁胶囊','牛奶','咽喉','清热','健脾','啤酒','小熊饼干'],
				
			    background: ['color1', 'color2', 'color3'],
				indicatorDots: true,
				autoplay: true,
				circular:true,			
				interval: 2000,
				duration: 500
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
   @import url("../../static/css/shouyei.css");
</style>
