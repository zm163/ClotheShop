<template>
	<tab-bar>
		<tab-bar-item path="/home">
				<img src="~assets/img/tabbar/icon01.png" alt="" slot="item-icon">
				<img src="~assets/img/tabbar/icon01_active.png" alt="" slot="item-icon-active">
				<div slot="item-text">主页</div>
		</tab-bar-item>
		<tab-bar-item path="/category">
				<img src="~assets/img/tabbar/icon02.png" alt="" slot="item-icon">
				<img src="~assets/img/tabbar/icon02_active.png" alt="" slot="item-icon-active">
				<div slot="item-text">分类</div>
		</tab-bar-item>
		<tab-bar-item path="/cart">
				<img src="~assets/img/tabbar/icon03.png" alt="" slot="item-icon">
				<img src="~assets/img/tabbar/icon03_active.png" alt="" slot="item-icon-active">
				<div slot="item-text">购物车</div>
		</tab-bar-item>
		<tab-bar-item path="/my">
				<img src="~assets/img/tabbar/icon04.png" alt="" slot="item-icon">
				<img src="~assets/img/tabbar/icon04_active.png" alt="" slot="item-icon-active">
				<div slot="item-text">我的</div>
		</tab-bar-item>
	</tab-bar>
</template>

<script>
	import TabBar from "components/common/tabbar/TabBar.vue"
	import TabBarItem from "components/common/tabbar/TabBarItem.vue"
	export default {
		name: 'MainTabBar',
		components: {
			TabBar,
			TabBarItem
		}
	}
</script>

<style>
</style>
