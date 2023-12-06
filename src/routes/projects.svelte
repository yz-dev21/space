<script>
	import Input from './input.svelte';
</script>

<div class="w-75">
	<span>Projects</span>
	<Input className="projects-input" placeHolder="> Add a new project..." />
</div>

<style>
	div {
		margin-left: 20%;
	}
	span {
		color: white;
		font-size: 400%;
		font-weight: 700;
	}
</style>
