<script>
	let visible = true;

	function toggle() {
		visible = !visible;
	}
</script>

{#if visible}
	<button on:click={toggle}>remove</button>
	<a on:click={toggle}>remove</a>
{:else}
	<button on:click={toggle}>add</button>
	<a on:click={toggle}>add</a>
{/if}
