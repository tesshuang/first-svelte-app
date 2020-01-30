<script>
	export let name;
	
	import Image from '../components/Image.svelte';
	import Modal from '../components/Modal.svelte';

</script>
<div class="container">
	<h1>Hello {name}</h1>
	<Image />
	<br/>
	<Modal />
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</div>

