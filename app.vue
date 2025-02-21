<script setup>
import { useCounterStore } from "#imports";

const store = useCounterStore();
</script>

<template>
	<h1 class="text-3xl font-bold underline">Hello world! {{ store.count }}</h1>
</template>
