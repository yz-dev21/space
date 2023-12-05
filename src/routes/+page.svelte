<script>
	import Home from './home.svelte';
	import Settings from './settings.svelte';
	import Projects from './projects.svelte';
	import BottomBtns from './bottomBtns.svelte';
</script>

<div class="container-fluid d-flex flex-column justify-content-between">
	<div class="row mt-5">
		<div class="col tab-content text-center">
			<div class="tab-pane fade show active" id="nav-home" role="tabpanel">
				<Home />
			</div>
			<div class="tab-pane fade" id="nav-settings" role="tabpanel">
				<Settings />
			</div>
			<div class="tab-pane fade" id="nav-projects" role="tabpanel">
				<Projects />
			</div>
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
