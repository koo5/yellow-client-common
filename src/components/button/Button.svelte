<script lang="ts">

	let { onClick, label } = $props();

</script>

bbb<button
	class="button"
	on:click={onClick}
>
	{#if label}
		<span class="label">{label}</span>
	{/if}
</button>button
