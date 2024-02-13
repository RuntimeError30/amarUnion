<script>
	import Body from '../../UserDashboard/body.svelte';
	import Profilesidebar from '../../UserDashboard/profilesidebar.svelte';
	import NAVBAR from '../../UserDashboard/sidebar.svelte';
</script>

<main class="bg-slate-100">
	<div class="grid grid-cols-12 gap-x-20">
		<NAVBAR />
		<Body />
		<Profilesidebar />
	</div>
</main>
