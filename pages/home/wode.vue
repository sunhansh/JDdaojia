<template>
	<!--  我的-->
	<view class="content">
		<!-- 头部 1-->
		<view class="toulv1">
			<!-- 设置图片 -->
			<view id="shezhi1">
				<image src="../../static/img/shezhi.png" class="shezhi2"></image>
			</view>
			<!-- 信息图片 -->
			<view id="xinxi1">
				<image src="../../static/img/xinxi.png" class="xinxi2"></image>
			</view>		
		</view>
		<!-- 头部 2 -->
		<view class="toulv2">
				<!-- 头像图片 -->
			<view id="touxiang1">
				<image src="../../static/img/JD.png" class="touxiang2"></image>
			</view>
			<!-- 登录/注册 -->
			<button class="dz" @click="dnenglu5">登录/注册</button>
		</view>
		<!-- 头部下方 -->
		<view class="touxia">
			<view id="qianbao1">
				 <image src="../../static/img/qianbao.png" class="qianbao2"></image>
				 <view class="zi">我的钱包</view>
			</view>
			<!-- 红包数量 -->
			<view class="shuliang0">
				 <view class="shuliang1">0</view>
				 <view class="shuliang2">红包</view>
			</view>
			<!-- 红包数量 -->
			<view class="shuliang0">
				 <view class="shuliang1">0</view>
				 <view class="shuliang2">优惠券</view>
			</view>
				<!-- 红包数量 -->
			<view class="shuliang0">
				 <view class="shuliang1">0</view>
				 <view class="shuliang2">白条</view>
			</view>
				<!-- 红包数量 -->
			<view class="shuliang0">
				 <view class="shuliang1">0</view>
				 <view class="shuliang2">仙豆</view>
			</view>
			
		</view>	
		
 <!-- 轮播图 -->		
	  <view class="uni-padding-wrap">
            <view class="page-section swiper">
                <view class="page-section-spacing">
                    <swiper class="swiper" :circular="circular" :indicator-dots="indicatorDots" :autoplay="autoplay" :interval="interval" :duration="duration">
                        <swiper-item>
                            <view class="swiper-item uni-bg-red">
								<image src="../../static/img/luenbo1.jpg" class="luenbotu"></image>
							</view>
                        </swiper-item>
                        <swiper-item>
                            <view class="swiper-item uni-bg-green">
								<image src="../../static/img/luenbo2.jpg" class="luenbotu"></image>
							</view>
                        </swiper-item>
                     
                    </swiper>
					
                </view>
            </view>
        </view>	 
		 
		 
		  <!-- 功能小图 -->
		    <view class="gnxioatu0">
				<view class="gnxioatu2"><image src="../../static/img/xin.png" class="gnxioatu"></image></view>
		    	 <view class="gnxioatu1">我的关注</view>		    	 
		    </view>
		 <view class="gnxioatu0">
			<view class="gnxioatu2"><image src="../../static/img/pingjia.png" class="gnxioatu"></image></view>
			 <view class="gnxioatu1">我的评价</view>		    	 
		</view>	
		<!-- 我的地址 -->
		 <view class="gnxioatu0">
			<view class="gnxioatu2"><image src="../../static/img/dizhi.png" class="gnxioatu"></image></view>
			 <view class="gnxioatu1">我的地址</view>		    	 
		</view>	
			<!-- 我的卡包 -->
		 <view class="gnxioatu0">
			<view class="gnxioatu2"><image src="../../static/img/kabao.png" class="gnxioatu"></image></view>
			 <view class="gnxioatu1">我的卡包</view>		    	 
		</view>	
		<!-- 横线 -->
		 <view class="xian"></view>
		 
		 <!-- 红包套餐 -->
		 <view class="gnxioatu0">
			<view class="gnxioatu2"><image src="../../static/img/hongbao.png" class="gnxioatu"></image></view>
			 <view class="gnxioatu1">红包套餐</view>		    	 
		</view>	
		 <!-- 我的奖励金 -->
		 <view class="gnxioatu0">
			<view class="gnxioatu2"><image src="../../static/img/qiandai.png" class="gnxioatu"></image></view>
			 <view class="gnxioatu1">我的奖励金</view>		    	 
		</view>	
		 <!-- 签到有惊喜 -->
	 <view class="gnxioatu0">
		<view class="gnxioatu2"><image src="../../static/img/qiandao.png" class="gnxioatu"></image></view>
		 <view class="gnxioatu1">签到有惊喜</view>		    	 
	</view>		
		 <!-- 退款/售后 -->
	 <view class="gnxioatu0">
		<view class="gnxioatu2"><image src="../../static/img/shouhou.png" class="gnxioatu"></image></view>
		 <view class="gnxioatu1">退款/售后</view>		    	 
	</view>
	<!-- 横线 -->
	 <view class="xian"></view>
	 
	 <!-- 客服反馈 -->
	  <view class="gnxioatu0">
	 	<view class="gnxioatu2"><image src="../../static/img/kefu.png" class="gnxioatu"></image></view>
	 	 <view class="gnxioatu1">客服反馈</view>		    	 
	 </view>
	 <!-- 帮助中心 -->
	 <view class="gnxioatu0">
	 	<view class="gnxioatu2"><image src="../../static/img/bangzhu.png" class="gnxioatu"></image></view>
	 	 <view class="gnxioatu1">客服反馈</view>		    	 
	 </view>
	 <!-- 配送员注册 -->
	  <view class="gnxioatu0">
	 	<view class="gnxioatu2"><image src="../../static/img/zhuce.png" class="gnxioatu"></image></view>
	 	 <view class="gnxioatu1">配送员注册</view>		    	 
	 </view>
	 <!-- 哒哒同城送 -->
	 <view class="gnxioatu0">
	 	<view class="gnxioatu2"><image src="../../static/img/pao.png" class="gnxioatu"></image></view>
	 	 <view class="gnxioatu1">哒哒同城送</view>		    	 
	 </view>
	<!-- 横线 -->
   <view class="xian"></view>
	<!-- 金融权益 -->
		 <view class="gnxioatu0">
			<view class="gnxioatu2"><image src="../../static/img/jinrong.png" class="gnxioatu"></image></view>
			 <view class="gnxioatu1">金融权益</view>		    	 
		</view>
	<!-- 掌声有礼 -->
	 <view class="gnxioatu0">
		<view class="gnxioatu2"><image src="../../static/img/zhangsheng.png" class="gnxioatu"></image></view>
		 <view class="gnxioatu1">掌声有礼</view>		    	 
	</view>
	<!-- 浦发有礼 -->
		 <view class="gnxioatu0">
			<view class="gnxioatu2"><image src="../../static/img/pufa.png" class="gnxioatu"></image></view>
			 <view class="gnxioatu1">浦发有礼</view>		    	 
		</view>
		
	</view>
</template>

<script>
	export default {
		// 数据
		data() {
			return {
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
	        dnenglu5(){
				uni.navigateTo({
				url:"login"
			   })				
			}
			
		}
		
	}
</script>

<style>
    @import url("../../static/css/wode.css");
</style>
