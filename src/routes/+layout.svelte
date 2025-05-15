<script lang="ts">
	import Sidebar from '../components/Sidebar.svelte';
	import '../app.css';
</script>

<svelte:head>
	<title>The Social!</title>
	<meta
		name="description"
		content="The Social is a social media website, designed to be for people to share their thoughts and ideas."
	/>
</svelte:head>
<Sidebar />
<slot />
