<template>
	<view class="content">
		<view>
			<!-- 点击只变颜色 -->	   
			  <button class="phone" :style={background:bgcolor2} @click="fn3('phone')">手机号快捷登录</button>				  
			  <button class="password" :style={background:bgcolor1} @click="fn3('password')">账号密码登录</button>
		 
		    
			<!-- 输入框外盒 -->
			<view class="dengneirong">
				<!-- 输入框 -->
				<input class="tishiyuju"  placeholder="请输入手机号(无需注册)" />
					  <!-- 手机小图 -->
				<view class="qiantu1">
					 <image class="qiantu2" src="../../static/img/shouji.png"></image>
				</view>
				<!-- 横线 -->
				<view class="hengxian"></view>
			</view>
			
		   <view class="dengneirong">
			       <!-- 提示 -->
			   <input class="tishiyuju" placeholder="未注册过的手机将自动保存为京东账户" />
			   	  <!-- 手机小图 -->
			   <view class="qiantu1">
			   	 <image class="qiantu2" src="../../static/img/gantan.png"></image>
			   </view>
			   <!-- 横线 -->
			   <view class="hengxian"></view>
		   </view>
				   
		   
		   <!-- 登录注册 -->
	<!-- 	   <input class="username" placeholder="请输入用户名"/>
		   <input class="mima" placeholder="请输入密码"/>
		   <button type="primary" size="mini" @click="denglu">登录</button>
		   <button type="primary" size="mini" @click="zhuce">注册</button> -->
		   
		   
	   </view>
		
	</view>
</template>

<script>
	export default {
		data(){
			return{
				// 点击只变颜色
				bgcolor2:'white',
				bgcolor1:'silver'
			}
			
			
		},
		onLoad() {
			
		},
		methods:{
			fn3(type){
				 if (type=='password') {
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
	@import url("../../static/css/denglu.css");
</style>
