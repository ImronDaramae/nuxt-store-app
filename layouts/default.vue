<template>
	<div>
		<VApp>
            <VAppBar app>
                <VToolbarTitle>My Nuxt App</VToolbarTitle>
            </VAppBar>
			<VMain>
				<slot />
			</VMain>
		</VApp>
	</div>
</template>