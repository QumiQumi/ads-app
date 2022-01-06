<template>
	<div id="app">
		<h1 class="text-center my-auto">
			Best place to shop what you want
			<br />
			Advertisment knows you better
		</h1>

		<card msg="" />
	</div>
</template>

<script>
import Card from "./components/Card.vue";

export default {
	name: "App",
	components: {
		Card,
	},
};
</script>

<style>
#app {
	background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
	background-size: 400% 400%;
	animation: gradient 15s ease infinite;
	height: 100%;
	padding: 4rem 2rem;
}

@keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}
</style>
