<template>
	<h1>我是新闻页</h1>
	<div>
		<ul>
		<li>
		<a v-link="{path:'/news/detail/001'}">新闻001</a>
		</li>
		<li>
		<a v-link="{path:'/news/detail/002'}">新闻002</a>
		</li>
		</ul>
	</div>
	<div>
		<router-view></router-view>
	<div>
</template>