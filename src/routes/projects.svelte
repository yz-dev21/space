<script>
	import Input from './input.svelte';
</script>

<div class="container text-center justify-content-center">
	<div class="row sticky-top">
		<span id="header">Projects</span>
	</div>
	<button class="btn btn-outline-black w-50 mt-4">
		<div class="row align-items-center mb-4">
			<div class="col text-start">
				<span id="project-title">ExampleProject</span>
			</div>
			<div class="col text-end">
				<span id="percentage-text">50%</span>
			</div>
		</div>
		<div class="row align-items-baseline">
			<div class="col text-start">
				<span id="dday-text">D-50</span>
			</div>
			<div class="col text-end">
				<span id="edit-date-text">2023-12-08</span>
			</div>
		</div>
	</button>
</div>

<style>
	#header {
		color: white;
		font-size: 350%;
		font-weight: 700;
	}
	.btn-outline-black {
		background-color: transparent;
		border-color: white;
		color: white;
	}
	.btn-outline-black:hover {
		background-color: white;
		color: black;
	}
	#project-title {
		font-size: 250%;
		font-weight: 700;
	}
	#percentage-text {
		font-size: 150%;
		font-weight: 700;
	}
	#dday-text {
		font-weight: 600;
	}
	#edit-date-text {
		font-weight: 600;
	}
</style>
