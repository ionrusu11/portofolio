<template>
	<div>
		<NuxtLayout>
			<header>
				<NuxtLink active-class="text-red-700" to="/">Home</NuxtLink> |
				<NuxtLink active-class="text-red-700" to="/projects"
					>Projects</NuxtLink
				>
				|
				<NuxtLink active-class="text-red-700" to="/about"
					>About</NuxtLink
				>
			</header>

			<NuxtPage />
		</NuxtLayout>
	</div>
</template>
