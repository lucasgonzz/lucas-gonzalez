<template>
	<div class="project box">
		<div class="img-container">
			<img src="@/assets/interfaz.png">
		</div>
		<div class="data-container">
			<p class="title">
				Interfaz
			</p>
			<p class="description">
				Interfaz es un spa que trabaja con una tienda construida en Wordpress. Recibe los pedidos de la api de Wordpress y los enlista para que se les asigne un armador, repartidor, zona de envió, etc.
			</p>
			<p>
				Fue diseñada y programada para una empresa de Rosario, <a clas="btn-link" href="https://cuatrosistemas.com.ar/" target="_blank">Cuatro Sistemas</a>, en la cual trabaje unos meses desarrollando esta app y agregando funcionalidad a otros proyectos de la empresa.
			</p>
			<b-button
			v-b-modal="'interfaz'"
			class="bg-purple">
				Ver en detalle
			</b-button>
		</div>
	</div>
</template>