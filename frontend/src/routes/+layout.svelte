<script lang="ts">
	import '../app.css';
	import { WindowMinimise } from '$lib/wailsjs/runtime';
	let { children } = $props();
</script>


<button
	class="absolute top-2 right-2 z-50 rounded-md bg-gray-200 p-2 text-gray-600 hover:bg-gray-300"
	onclick={() => WindowMinimise()}
>
	<span class="material-icons">close</span>
</button>
{@render children()}
