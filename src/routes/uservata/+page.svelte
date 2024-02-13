<script>

	import Profilesidebar from '../../UserDashboard/profilesidebar.svelte';
	import NAVBAR from '../../UserDashboard/sidebar.svelte';
	import Vata from '../../UserVata/vata.svelte';

</script>

<main class="bg-slate-100">
	<div class="grid grid-cols-12 gap-x-20">
		<NAVBAR />
		<Vata />
		<Profilesidebar />
	</div>
</main>