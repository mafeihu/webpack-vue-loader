<template>
	<div id="app">
		<h1>vue-loader+vue-router</h1>
		<div id ="box">
			<a v-link="{path:'/home'}">主页</a>
			<a v-link="{path:'/news'}">新闻页</a>
		</div>
		<router-view></router-view>
	</div>
</template>
<script>
</script>
<style>
	body{
		background: #ccc
	}
	.v-link-active{
		color:red;
		font-size:20px
	}
</style>