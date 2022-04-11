<script setup lang="ts">
import Menu from "./components/Menu.vue"
import Sidebar from "./components/Sidebar.vue"
import Canvas from "./components/Canvas.vue"
import Palette from "./components/Palette.vue"
import Footer from "./components/Footer.vue"
</script>

<template>
	<div class="flex flex-col justify-between h-screen">
		<Menu />
		<main class="flex flex-grow-1 h-full">
			<Sidebar />
			<Canvas />
		</main>
		<footer class="flex flex-col">
			<Palette />
			<Footer />
		</footer>
	</div>
</template>

