<template>
  <div class="min-h-screen flex items-center justify-center bg-amber-100">
    <img
      src="https://c.tenor.com/WuOwfnsLcfYAAAAC/star-wars-obi-wan-kenobi.gif"
    />

    <div class="rounded-lg border bg-white">
      <pre>

         {{ data }}
        </pre
      >

      <p class="text-7xl">{{ data.name }}</p>
    </div>
  </div>
</template>

<script setup>
const { data } = await useFetch("https://swapi.dev/api/people/1");

console.log(data.value);
</script>
