<template>
	<NuxtLayout>
		<NuxtPage />
	</NuxtLayout>
</template>

<style>
	.page-enter-active,
	.page-leave-active {
		transition: all 0.4s;
	}
	.page-enter-from,
	.page-leave-to {
		opacity: 0;
		transform: translateX(-100px);
		filter: blur(2px);
	}
	.page-enter-from {
		transform: translateX(150px);
	}
</style>
