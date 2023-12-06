<script>
    export let className;
    export let placeHolder;
</script>

<div class="input-group border-bottom border-2 {className}">
	<form>
		<input type="text" class="bg-transparent text-white" spellcheck="false" placeholder={placeHolder} />
	</form>
</div>

<style>
	.input-group {
		font-weight: 600;
		font-size: 250%;
		color: white;
	}
	.input-group input,
	.input-group input:focus {
		outline: none;
		border: none;
	}
	.projects-input {
		width: 85%;
	}
</style>
