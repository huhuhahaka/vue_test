<template>
	<h1 class="red">大家好！！！ {{msg}} {{name}}</h1>
</template>

<script>
	export default {
		name: 'test',
		props: {
			msg: {
				type: String,
				default: "我是"
			}
		},
		methods: {

		},
		data() {
			return {
				name: "Jason"
			}
		}
	}
</script>

<style>
	.red {
		color: red;
	}
</style>
