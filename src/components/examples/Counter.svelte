<!-- js -->
<script>
	let count = 0;
</script>

<!-- html -->
<button on:click={() => (count += 1)}> Increment </button>
<p>{count}</p>

<!-- css -->
<style>
	button {
		background: aliceblue;
		color: darkgray;
	}
</style>
