<template>
	<b-row
	class="projects">
		<b-col>
			<p class="main-title">
				Mis trabajos
			</p>
			<miregistrodeventas></miregistrodeventas>
			<tienda></tienda> 
		</b-col>
	</b-row>
</template>
<script>
import Miregistrodeventas from '@/components/home/components/projects/Miregistrodeventas'
import Tienda from '@/components/home/components/projects/Tienda'
export default {
	components: {
		Miregistrodeventas,
		Tienda,
	},
}
</script>
<style lang="sass">
.projects
	.main-title
		font-size: 1.6em
		text-align: center
		margin-top: 1em
</style>