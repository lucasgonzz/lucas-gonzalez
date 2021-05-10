<template>
<div class="home">
	<tienda></tienda>
	<miregistrodeventas></miregistrodeventas>
	<presentation></presentation>
	<projects></projects>
</div>
</template>

<script>
import Presentation from '@/components/home/components/Presentation'
import Projects from '@/components/home/components/Projects'
import Miregistrodeventas from '@/components/home/modals/Miregistrodeventas'
import Tienda from '@/components/home/modals/Tienda'

export default {
	name: 'Home',
	components: {
		Presentation,
		Projects,
		Miregistrodeventas,
		Tienda,
	}
}
</script>
