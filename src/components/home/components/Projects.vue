<template>
	<b-row>
		<b-col>
			<p class="main-title">
				Mis trabajos
			</p>
			<div class="projects">
				<miregistrodeventas></miregistrodeventas>
				<tienda></tienda> 
				<interfaz></interfaz> 
				<truquera></truquera> 
			</div>
		</b-col>
	</b-row>
</template>
<script>
import Miregistrodeventas from '@/components/home/components/projects/Miregistrodeventas'
import Tienda from '@/components/home/components/projects/Tienda'
import Interfaz from '@/components/home/components/projects/Interfaz'
import Truquera from '@/components/home/components/projects/Truquera'
export default {
	components: {
		Miregistrodeventas,
		Tienda,
		Interfaz,
		Truquera,
	},
}
</script>