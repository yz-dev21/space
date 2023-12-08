<script>
	import Modal from './modal.svelte';
</script>

<div class="container text-center">
	<div class="sticky-top">
		<div class="row">
			<span id="header">Projects</span>
		</div>
		<div class="row justify-content-center">
			<button type="button" class="btn btn-outline-black w-50 mt-4 mb-4 border border-3" data-bs-toggle="modal" data-bs-target="#exampleModal">
				<div class="row mt-3 mb-3">
					<span class="material-symbols-outlined">add_circle</span>
				</div>
			</button>
		</div>
	</div>
	<ul>
		{#each { length: 10 } as _, i}
			<li>
				<button class="btn btn-outline-black w-50 mt-4 text-start">
					<div class="row align-items-center mb-5">
						<div class="col text-start">
							<span id="project-title">Example예시{i}</span>
						</div>
						<div class="col text-end">
							<span id="edit-date-text">2023-12-08</span>
						</div>
					</div>
					<div class="row align-items-baseline">
						<div class="col text-start">
							<span id="dday-text">D-50</span>
						</div>

						<div class="col text-end">
							<span id="percentage-text">50%</span>
						</div>
					</div>
				</button>
			</li>
		{/each}
	</ul>
	<Modal />
</div>

<style>
	.sticky-top {
		background-color: black;
	}
	#header {
		color: white;
		font-size: 350%;
		font-weight: 700;
	}
	.material-symbols-outlined {
		font-size: 300%;
	}
	ul {
		list-style: none;
		padding-left: 0;
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
		font-size: 150%;
		font-weight: 600;
	}
	#edit-date-text {
		font-weight: 600;
	}
</style>
