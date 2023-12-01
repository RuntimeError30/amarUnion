<script>
	import { onMount } from 'svelte';
	import Chart from 'chart.js';

	let chart;

	onMount(() => {
		const ctx = document.getElementById('myChart').getContext('2d');

		chart = new Chart(ctx, {
			type: 'line',
			data: {
				labels: ['January', 'February', 'March', 'April', 'May'],
				datasets: [
					{
						label: '',
						borderColor: 'rgb(249, 116, 21)',
						data: [0, 10, 5, 2, 20]
					}
				]
			}
		});
	});
</script>

<div>
	<canvas id="myChart" width="500" height="200"></canvas>
</div>

<style>
</style>
