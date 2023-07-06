<script lang="ts">
	export let obrazky: string[];
	let index = 0;
</script>

<button on:click={() => index--}>Předchozí</button>
<img src={obrazky[index]} />
<button on:click={() => index++}>Další</button>
