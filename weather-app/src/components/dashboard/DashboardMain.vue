<script>
import DashboardHeader from './DashboardHeader.vue'
import DashboardInfo from './DashboardInfo.vue'

export default {
	name: 'DashboardMain',
	components: {
		DashboardHeader,
		DashboardInfo,
	},
}
</script>

<template>
	<div class="dashboard-main">
		<DashboardHeader />
		<DashboardInfo />
	</div>
</template>

<style></style>
