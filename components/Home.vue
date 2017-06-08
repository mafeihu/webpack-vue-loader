<template>
	<h1>我是主页</h1>
	<div>
		<a v-link="{path:'/home/login'}">用户登录</a>
		<a v-link="{path:'/home/reg'}">用户注册</a>
	</div>
	</div class="box">
		<router-view></router-view>
	</div>
</template>
