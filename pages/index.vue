<script setup>
useHead({
	title: "Wolf Fight Club",
});

const wolfFightClubHistory = [
	{
		title: "Założenie klubu",
		date: "2005",
		description:
			"Wolf Fight Club został założony w 2005 roku, oferując treningi sztuk walki dla entuzjastów sportów walki.",
	},
	{
		title: "Pierwszy duży sukces",
		date: "2010",
		description: "W 2010 roku klub odniósł swój pierwszy znaczący sukces, zdobywając regionalne mistrzostwa.",
	},
	{
		title: "Otwarcie nowej siedziby",
		date: "2015",
		description: "W 2015 roku klub przeniósł się do nowej, większej siedziby, aby pomieścić rosnącą liczbę członków.",
	},
	{
		title: "Międzynarodowe uznanie",
		date: "2020",
		description: "W 2020 roku Wolf Fight Club zyskał międzynarodowe uznanie, organizując międzynarodowe turnieje.",
	},
];
</script>

<template>
	<div class="container mx-auto py-4">
		<Hero />
		<ClubHistory :items="wolfFightClubHistory" />
	</div>
</template>
