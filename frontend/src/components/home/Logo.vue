<script setup lang="ts">
import logo from '@/assets/logo.jpg'
</script>

<template>
	<div>
		<img
			class="logo"
			:src="logo"
			alt="Vikunja"
		>
	</div>
</template>

<style lang="scss" scoped>
.logo {
	color: var(--logo-text-color);
	max-inline-size: 168px;
	max-block-size: 48px;
	border-radius: 9999px;
}
</style>
