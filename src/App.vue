<template>
	<QLayout view="hHh lpR fFf">
		<QPageContainer>
			<RouterView id="View" />
		</QPageContainer>
	</QLayout>
</template>

<script setup>
import { onMounted, nextTick } from 'vue';

onMounted(() => {
	nextTick(Init);
});

function Init() {
	console.log(`App init: ${import.meta.env.VITE_BUILD_TARGET}:${import.meta.env.VITE_BUILD_VERSION}:${import.meta.env.MODE}`);
}
</script>

<style lang="scss">
@import '@quasar/extras/mdi-v7/mdi-v7.css';
@import 'quasar/src/css/index.sass';

@import '@/core/globals';
@import '@/core/core';
</style>
