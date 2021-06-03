<template>
	<Header />

	<div class="container">
		<h1>Hello</h1>
	</div>
</template>

<script>
	import Header from "./components/Header";

	export default {
		name: "App",
		components: {
			Header,
		},
	};
</script>

<style>
	* {
		box-sizing: border-box;
		margin: 0;
		padding: 0;
	}

	.container {
		max-width: 1200px;
		margin: 30px auto;
		overflow: auto;
		min-height: 300px;
	}
</style>
