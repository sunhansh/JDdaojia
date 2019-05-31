<template>
	<view class="content">
		<view>
			<input type="text" placeholder="请输入用户名" v-model="username">
			<view>
				<input :type="flag" placeholder="请输入密码" v-model="password">
				<uni-icon type="eye" size="20" @click='fn'></uni-icon>
			</view>
			<button @click="login">登录</button>
			
		</view>
	</view>
</template>

<script>
	import uniIcon from "@dcloudio/uni-ui/lib/uni-icon/uni-icon.vue"
	export default {
		components: {uniIcon},
		data() {
			return {
				username: 'lhx',
				password:'123456',
				flag:'password'
			}
		},
		onLoad() {

		},
		methods: {
		
			fn(){
				if(this.flag=='password'){
					this.flag='text'
				}else{
					this.flag='password'
				}
			},
			login(){			
			
			//登录条件
			if (this.username.length <= 0) {
				uni.showToast({
					icon: 'none',
					title: '请输入用户名',
					duration: 1000
				});
				return;
			}
			if (this.password.length <= 0) {
				uni.showToast({
					icon: 'none',
					title: '请输入密码',
					duration: 1000
				});
				return;
			}
           if ((this.username!="lhx") && (this.password!="123456")) {
           	   uni.showToast({
					icon: 'none',
					title: '用户名或密码不正确',
					duration: 1000
           	    });
           } else{
			 uni.reLaunch({
			 	url:"index"
			 })
			  uni.showToast({
			  	title: '登录成功',
			  	duration: 1000
			  })
			  
            }
			
		 }

	   }
	}
</script>

<style>
	@import url("../../static/css/login.css");
</style>
