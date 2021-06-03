<template>
<div class="home">
	<tienda></tienda>
	<miregistrodeventas></miregistrodeventas>
	<interfaz></interfaz>
	<presentation></presentation>
	<skils></skils>
	<projects></projects>
</div>
</template>

<script>
import Presentation from '@/components/home/components/Presentation'
import Skils from '@/components/home/components/Skils'
import Projects from '@/components/home/components/Projects'
import Miregistrodeventas from '@/components/home/modals/Miregistrodeventas'
import Tienda from '@/components/home/modals/Tienda'
import Interfaz from '@/components/home/modals/Interfaz'

export default {
	name: 'Home',
	components: {
		Presentation,
		Skils,
		Projects,
		Miregistrodeventas,
		Tienda,
		Interfaz,
	}
}
</script>
