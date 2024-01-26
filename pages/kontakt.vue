<script setup>
useHead({
	title: "Kontakt - Wolf Fight Club",
});
</script>

<template>
	<div class="container mx-auto flex items-center justify-center py-14">
		<div class="card shrink-0 w-full max-w-md shadow-xl bg-base-300">
			<form class="card-body">
				<div class="form-control">
					<label class="label">
						<span class="label-text">Imię</span>
					</label>
					<input
						type="name"
						placeholder="Jan"
						class="input input-bordered"
						required
					/>
				</div>
				<div class="form-control">
					<label class="label">
						<span class="label-text">Email</span>
					</label>
					<input
						type="email"
						placeholder="jan-kowalski@gmail.com"
						class="input input-bordered"
						required
					/>
				</div>
				<div class="form-control">
					<label class="label">
						<span class="label-text">Wiadomość</span>
					</label>
					<textarea
						placeholder="Cześć!"
						class="textarea textarea-bordered"
						required
					/>
				</div>
				<div class="form-control mt-6">
					<button class="btn btn-primary">Wyślij</button>
				</div>
			</form>
		</div>
	</div>
</template>
