<template>
	<div id="app">

		<DisplayStatus/>

	</div>
</template>

<script>
	import DisplayStatus from './components/DisplayStatus.vue'

	export default {
		name: 'app',
		components: {
			DisplayStatus
		}
	}
</script>

<style>
	#app {
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
		margin-top: 60px;
	}
</style>
