<script>
import DashboardDate from './DashboardDate.vue'
import DashboardTemp from './DashboardTemp.vue'
import DashboardTime from './DashboardTime.vue'

export default {
	name: 'DashboardInfo',
	components: {
		DashboardTemp,
		DashboardDate,
		DashboardTime,
	},
}
</script>

<template>
	<div class="dashboard-info">
		<DashboardTemp />
		<DashboardDate />
		<DashboardTime />
	</div>
</template>
<style></style>
