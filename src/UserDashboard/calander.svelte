<script>
	import { InlineCalendar } from 'svelte-calendar';
	const theme = {
		calendar: {
			width: '200px',
			shadow: '0px 0px 5px rgba(0, 0, 0, 0.25)'
		}
	};
</script>

<InlineCalendar {theme} />
