<script>
	// export let name;

	import "../node_modules/materialize-css/dist/css/materialize.min.css";
	import "../node_modules/materialize-css/dist/js/materialize.min.js";
	import { Router, Route } from "svelte-routing";

	import NavBar from './layout/NavBar.svelte'; 
	
	import Home from "./pages/Home.svelte";
	import About from './pages/About.svelte';
	import Contact from "./pages/Contact.svelte";
</script>

<Router>
	<NavBar />
	<div class="container">
		<Route path="contact" component="{Contact}" />
		<Route path="about" component="{About}" />
		<Route path="/"><Home /></Route>
</div>
</Router>

<style>

</style>