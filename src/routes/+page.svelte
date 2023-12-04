<script>
	import Home from './home.svelte';
	import BottomBtns from './bottomBtns.svelte';
</script>

<div class="container-fluid d-flex flex-column justify-content-between">
	<div class="row text-center align-items-center flex-grow-1">
		<div class="col">
			<Home />
		</div>
	</div>
	<div class="row justify-content-center mb-3">
		<div class="col-2">
			<BottomBtns />
		</div>
	</div>
</div>

<style>
	.container-fluid {
		width: 100vw;
		height: 100vh;
	}
	:global(body) {
		background-color: black;
	}
	:global(*) {
		font-family: 'Pretendard';
	}
	:global(::selection) {
		background-color: white;
		color: black;
	}
</style>
