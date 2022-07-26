<template>
	<div id="app" class="container">
		<Card>
			<template #image>
				<img
					src="../src/assets/image-qr-code.png"
					alt="bar code"
					class="component__img"
				/>
			</template>
			<template #title>
				<h1 class="heading">
					Improve your front-end skills by building projects
				</h1>
			</template>
			<template #description>
				<p class="description">
					Scan the QR code to visit Frontend Mentor and take your
					coding skills to the next level
				</p>
			</template>
		</Card>
		<div class="attribution">
			Challenge by
			<a
				href="https://www.frontendmentor.io?ref=challenge"
				target="_blank"
				>Frontend Mentor</a
			>. Coded by <a href="#">Alfred Thompson Ovie</a>.
		</div>
	</div>
</template>

<script>
import Card from "./components/CardComponent.vue";

export default {
	name: "App",
	components: {
		Card,
	},
};
</script>

<style lang="scss">
@import "./styles/global.scss";
</style>
