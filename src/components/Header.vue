<template>
	<header>
		<img alt="nm-d logo" src="../assets/nm-design.png" />
		<h1>Testing App</h1>
	</header>
</template>

<script>
	export default {
		name: "Header",
	};
</script>

<style scoped>
	header {
		display: flex;
		justify-content: space-around;
		text-align: center;
		background: #2e856e;
		padding: 15px 0;
	}

	h1 {
		color: #fff;
	}
</style>
