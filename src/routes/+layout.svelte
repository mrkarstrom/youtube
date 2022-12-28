<script>
	import '../app.css';
	import Header from '../components/Header.svelte';
</script>

<div class="page-wrapper flex flex-col items-center justify-center w-full h-full">
	<Header />
	<slot />
</div>
