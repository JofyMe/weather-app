<script>
import DashboardIcon from './DashboardIcon.vue'
import DashboardSwitch from './DashboardSwitch.vue'

export default {
	name: 'DashboardHeader',
	components: {
		DashboardIcon,
		DashboardSwitch,
	},
}
</script>

<template>
	<div class="dashboard-header">
		<DashboardIcon />
		<DashboardSwitch />
	</div>
</template>

<style>
.dashboard-header {
	display: flex;
}
</style>
