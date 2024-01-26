<script setup>
const navLinks = [
	{ url: "/", title: "Strona główna" },
	{ url: "/#historia", title: "Historia" },
	{ url: "/kontakt", title: "Kontakt" },
];
</script>
<template>
	<div>
		<Navbar :links="navLinks" />
		<NuxtPage />
		<Footer />
	</div>
</template>

