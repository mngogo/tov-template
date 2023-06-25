<template>
	<canvas id="canvas" style="width: 500px; height: 500px" />
</template>
<script setup lang="ts">
// import useEngine from '~/composables/useEngine'

onMounted(() => {
	useEngine('canvas')
})
</script>
