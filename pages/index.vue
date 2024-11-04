<script setup>
const route = useRoute();
</script>
<template>
	<div>
		<h1>Welcome to Nuxt.js</h1>
		<p>目前路由的路徑 - route.fullPath 為: {{ route.fullPath }}</p>
	</div>
</template>
<style scoped></style>
