<script>
	import Nav from '../components/Nav.svelte';
	import Footer from '../components/Footer.svelte';

	export let segment;
</script>

<style lang="scss" global>
	@import "../style/global.scss";
</style>

<Nav {segment}/>

<main>
	<slot></slot>
</main>

<Footer />