<template>
	<view class="content">		
		<view>
			<!-- 横向选项卡 -->
			<wuc-tab :tab-list="tabList" :tabCur.sync="TabCur" @change="tabChange" textFlex='true'></wuc-tab>
			<view v-if="TabCur==0">
				<guanzhu></guanzhu>
			</view>
			<view v-else-if="TabCur==1">
				<shipu></shipu>
			</view>
			<view v-else-if="TabCur==2">
				<tuijian></tuijian>
			</view>
			<view v-else-if="TabCur==3">
				<shishang></shishang>
			</view>
			<view v-else-if="TabCur==4">
			    <shenghuo></shenghuo>
			</view>
		</view>
		
	</view>
</template>

<script>
	
	import WucTab from '@/components/wuc-tab/wuc-tab.vue';
	import guanzhu from '../faxian/guanzhu.vue'
	import shipu from '../faxian/shipu.vue'
	import tuijian from '../faxian/tuijian.vue'
	import shishang from '../faxian/shishang.vue'
	import shenghuo from '../faxian/shenghuo.vue'
	export default {
	  components: {WucTab,guanzhu,shipu,tuijian,shishang,shenghuo},
		data(){
         return {
			TabCur: 0,
	        tabList: [{ name: '关注' }, { name: '食谱' }, { name: '推荐' },{ name: '时尚美妆' }, { name: '生活' }],
	      }},
   
		onLoad() {
			
		},
		methods:{		 
		 tabChange(index) {
		 	this.TabCur = index;
		 }
		 
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
