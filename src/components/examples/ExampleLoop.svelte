<script>
	let people = ['John', 'Jane', 'Bob'];
</script>

<div>
	<ul>
		{#each people as person}
			<li>{person}</li>
		{/each}
	</ul>
</div>
