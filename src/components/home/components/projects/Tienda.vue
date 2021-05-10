<template>
	<div class="project box">
		<div class="img-container">
			<img src="@/assets/tienda.jpg">
		</div>
		<div class="data-container">
			<p class="title">
				Tienda
			</p>
			<p class="description">
				Tienda es una tienda virtual que funciona sincronizadamente con miregistrodeventas.com
			</p>
			<p>
				Cada usuario de miregistrodeventas puede tener una tienda online, funcionando con su propio dominio
			</p>
			<div>
				<b-button
				v-b-modal="'tienda'"
				variant="success">
					Preview
				</b-button>
			</div>
		</div>
	</div>
</template>
<script>
export default {
}
</script>