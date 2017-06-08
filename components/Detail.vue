<template>
	<strong>
		{{$route.params | json}}
		<br>
		{{$route.query | json}}
		<br>
		{{$route.path | json}}
	</strong>
</template>