<template>
	<div>
		<h1>Project id: {{ idd }}</h1>
	</div>
</template>

<script>
export default {
	data() {
		return {
			project: {},
			idd: this.$route.params.id,
		}
	},
}
</script>

<style></style>
