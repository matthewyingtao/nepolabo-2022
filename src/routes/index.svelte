<script>
	import Counter from '../components/examples/Counter.svelte';
	import ExampleLoop from '../components/examples/ExampleLoop.svelte';
</script>

<h1>Nepolabo page</h1>
<nav>
	<a href="/nene">Nene</a>
	<a href="/polka">Polka</a>
	<a href="/botan">Botan</a>
	<a href="/lamy">Lamy</a>
	<a href="/2021">old page</a>
</nav>
<Counter />
<ExampleLoop />

<style>
	nav {
		display: flex;
		gap: 2rem;
	}
</style>
