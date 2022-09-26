<template>
	<main class="max-w-3xl min-h-screen mx-auto">
		<slot />
	</main>
</template>

<script lang setup>
useHead({
	bodyAttrs: {
		class: 'bg-amber-100',
	},
})
</script>
