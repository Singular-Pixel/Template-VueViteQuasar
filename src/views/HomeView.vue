<template>
	<QPage data-view="Home" class="colorScrollbars">
		<div class="q-pa-xl row justify-center">
			<div class="gt-sm col-auto"></div>
			<div class="col-xs-12 col-md-8 flexCenter vert">
				<svg id="HexLogo" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 1000 1000" style="enable-background:new 0 0 1000 1000;" xml:space="preserve">
					<polygon points="500,0 933,250 933,750 500,1000 67,750 67,250" fill="#2E5F9C" />
					<circle cx="500" cy="500" r="50" fill="#F5F5F5" />
					<path d="M500,280L760,280" fill="none" stroke="#F5F5F5" stroke-width="101" stroke-linecap="round" />
					<path d="M760,280L760,720" fill="none" stroke="#F5F5F5" stroke-width="101" stroke-linecap="round" />
					<path d="M500,720L240,720" fill="none" stroke="#F5F5F5" stroke-width="101" stroke-linecap="round" />
					<path d="M500,720L240,720" fill="none" stroke="#F5F5F5" stroke-width="101" stroke-linecap="round" />
					<path d="M240,720L240,280" fill="none" stroke="#F5F5F5" stroke-width="101" stroke-linecap="round" />
					<path d="M420,420C380,360,420,280,500,280" fill="none" stroke="#F5F5F5" stroke-width="101" stroke-linecap="round" />
					<path d="M580,580C620,640,580,720,500,720" fill="none" stroke="#F5F5F5" stroke-width="101" stroke-linecap="round" />
				</svg>
				<h1 class="q-pt-xl text-h2 titleFont text-center">Template - VueViteQuasar</h1>
			</div>
			<div class="gt-sm col-auto"></div>
		</div>
		<div class="q-pa-xl row justify-center">
			<div class="gt-sm col-auto"></div>
			<div class="col-xs-12 col-md-8">
				<p class="text-body1">This template has been built to quickly spin up new front-end projects with zero initial configuration required.<br>Pre-packaged & configured packages include the main 3 mentioned in the title:</p>
				<ul>
					<li class="q-mt-md">
						<span class="text-body1 text-weight-bold">Vite 5 (<a href="https://vitejs.dev/" target="_blank">https://vitejs.dev/</a>)</span>
						<p class="text-body1">Front-end developer tooling with local server, dependency resolving & bundling, and hot module replacement.</p>
					</li>
					<li class="q-mt-md">
						<span class="text-body1 text-weight-bold">Vue 3 (<a href="https://vuejs.org/" target="_blank">https://vuejs.org/</a>)</span>
						<p class="text-body1">Componentized & reactive JavaScript framework built for ease-of-use, speed, and to be incrementally adoptable.</p>
					</li>
					<li class="q-mt-md">
						<span class="text-body1 text-weight-bold">Quasar 2 (<a href="https://quasar.dev/" target="_blank">https://quasar.dev/</a>)</span>
						<p class="text-body1">Enterprise-ready cross-platform UI & component framework for Vue.</p>
					</li>
				</ul>
				<p class="text-body1">Also includes: <span class="text-weight-bold">ESLint</span> & <span class="text-weight-bold">Prettier</span> for code formatting and maintaining best practices, <span class="text-weight-bold">SASS</span> CSS preprocessor, <span class="text-weight-bold">Vue Router</span> to handle routing for single page web applications, and <span class="text-weight-bold">Pinia</span> for state management.</p>
			</div>
			<div class="gt-sm col-auto"></div>
		</div>
		<div class="q-pa-xl row justify-center">
			<div class="gt-sm col-auto"></div>
			<div class="col-xs-12 col-md-8 flexCenter vert">
				<h1 class="q-pt-xl text-h2 titleFont text-center">How To Use</h1>
			</div>
			<div class="gt-sm col-auto"></div>
		</div>
		<div class="q-pa-xl row justify-center">
			<div class="gt-sm col-auto"></div>
			<div class="col-xs-12 col-md-8">
				<p class="text-body1">To get started with this template for your own project, simply:</p>
				<ul>
					<li class="q-mt-md text-body1">
						Clone this repo to your new project directory
					</li>
					<li class="q-mt-md text-body1">
						Update the "name" field in the "package.json" file to reflect the name of your new project
					</li>
					<li class="q-mt-md text-body1">
						Run "npm i" to install all used packages, then "npm run dev" to start the Vite development server
					</li>
				</ul>
			</div>
			<div class="gt-sm col-auto"></div>
		</div>
	</QPage>
</template>

<script setup>
import { onMounted, nextTick } from 'vue';

onMounted(() => {
	nextTick(Init);
});

function Init() {
	
}
</script>

<style lang="scss">
@import '@/core/globals';

#View[data-view="Home"] {

	#HexLogo {
		max-width: 128px;
	}
}
</style>
