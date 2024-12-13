<script>
export default {
	name: 'DashboardTemp',
}
</script>

<template>
	<div class="dashboard-temp">
		<h1>27</h1>
		<h5>° C</h5>
	</div>
</template>

<style>
.dashboard-temp {
	display: flex;
	line-height: 0;
	color: white;
	text-shadow: -2px 1px #7b7b7b;
}

.dashboard-temp h1 {
	font-size: 128px;
	font-weight: 100;
}

.dashboard-temp h5 {
	font-size: 24px;
	font-weight: 100;
}
</style>
