<script setup>
import Dashboard from './components/dashboard/Dashboard.vue'
import Extra from './components/extra/Extra.vue'
</script>

<template>
	<div class="wrapper">
		<Dashboard />
		<Extra />
	</div>
</template>

<style scoped>
.wrapper {
	width: 800px;
	max-width: 100%;
	padding: 64px;
}
</style>
