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
				Se trata de una tienda virtual que funciona de manera sincronizada con Miregistrodeventas.
			</p>
			<p>
				Cada usuario de Miregistrodeventas puede tener una tienda online, funcionando con su propio dominio.
			</p>
			<b-button
			v-b-modal="'tienda'"
			variant="success">
				Ver en detalle
			</b-button>
		</div>
	</div>
</template>