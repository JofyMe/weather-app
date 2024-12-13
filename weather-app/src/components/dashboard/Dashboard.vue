<script>
import DashboardMain from './DashboardMain.vue'
import DashboardWeek from './DashboardWeek.vue'

export default {
	name: 'Dashboard',
	components: {
		DashboardMain,
		DashboardWeek,
	},
}
</script>

<template>
	<div class="dashboard">
		<DashboardMain />
		<DashboardWeek />
	</div>
</template>

<style>
.dashboard {
	display: flex;
}
</style>
