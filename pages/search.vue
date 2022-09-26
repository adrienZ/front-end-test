<template>
	<section>
		<input class="w-full mt-6 p-3 rounded-lg" />

    <pre class="bg-orange-500/20 mt-8 text-xs p-6">{{data}}</pre>
	</section>
</template>

<script setup>
const { data } = await useFetch('https://swapi.dev/api/people/1')

console.log(data.value)
</script>
