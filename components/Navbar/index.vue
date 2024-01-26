<script setup>
import { defineProps } from "vue";

const props = defineProps({
	links: {
		type: Array,
		required: true,
	},
});
console.log(props.links)
</script>

<template>
	<div class="navbar bg-base-100 w-100">
		<div class="flex-1">
			<a
				href=""
				class="btn btn-ghost text-xl"
			>
				<span class="text-red-700">Wolf</span>
				Fight Club
			</a>
		</div>
		<div class="flex-none">
			<ul class="menu menu-horizontal px-1">
				<li
					v-for="link in props.links"
					:key="link.url"
				>
					<a :href="link.url">{{ link.title }}</a>
				</li>
			</ul>
		</div>
	</div>
</template>
