<script>
	import Header from './components/Header.svelte'
	import Content from './components/Content.svelte';
	import Body from './components/Body.svelte';
</script>
<main>
	<Content>
		<div slot="header">
			<Header/>
		</div>
		<div slot="body">
			<Body />
		</div>
	</Content>
</main>

<style>
	@import "/courses/public/fonts.css";
</style>