<template>
	<div class="card">
		{{script}}
	</div>
</template>

<script>
export default {
	name: "Card",
	props: {
		script: String,
	},
};
</script>

<style lang="scss">
.card {
	min-height: 300px;
	min-width: 200px;
	box-shadow: 0px 6px 10px rgba(0, 0, 0, 0.25);
	transition: all 0.2s;
	background-color: #ffff;
}
</style>
