<ul class="nav nav-pills nav-fill gap-2 small bg-black rounded-5" role="tablist">
	<li class="nav-item" role="presentation">
		<button
			class="nav-link btn btn-outline-black rounded-5"
			data-bs-toggle="tab"
			data-bs-target="#nav-settings"
			type="button"
			role="tab"
			aria-selected="false"><span class="material-symbols-outlined">brush</span></button
		>
	</li>
	<li class="nav-item" role="presentation">
		<button
			class="nav-link active btn btn-outline-black rounded-5"
			data-bs-toggle="tab"
			data-bs-target="#nav-home"
			type="button"
			role="tab"
			aria-selected="true"><span class="material-symbols-outlined">home</span></button
		>
	</li>
	<li class="nav-item" role="presentation">
		<button
			class="nav-link btn btn-outline-black rounded-5"
			data-bs-toggle="tab"
			data-bs-target="#nav-projects"
			type="button"
			role="tab"
			aria-selected="false"><span class="material-symbols-outlined">checklist</span></button
		>
	</li>
</ul>

<style>
	.bg-black {
		background-color: black;
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
	ul {
		--bs-nav-link-color: white;
		--bs-nav-pills-link-active-color: black;
		--bs-nav-pills-link-active-bg: white;
	}
	button:hover {
		color: white;
	}
</style>
