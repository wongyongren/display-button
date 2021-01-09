<template>
	<div class="status" v-if="!(mode === 'run' )">
		<span class="text">Stop</span>
	</div>
	<div class="status" v-else>
		<span class="text">Run</span>
	</div>
</template>

<script>
	import SwitchButton from './SwitchButton.vue'

	export default {
		name: 'app',
		props: ['mode'],
		components: {
			SwitchButton
		}
	}
</script>

<style>
	.text {
		width: 105px;
		height: 50px;
		margin-left: -20px;
		border: 1px solid #aed581;
		border-radius: 10px;
		z-index: 4;
		display: inline-flex;
		align-items: center;
		justify-content: center;
	}
</style>
