<template>
	<div class="project box">
		<div class="img-container">
			<img src="@/assets/miregistrodeventas.png">
		</div>
		<div class="data-container">
			<p class="title">
				Mis registro de ventas
			</p>
			<p class="description">
				Miregistrodeventas es una aplicación contable, usada por comercios con venta al publico y distribuidoras. 
			</p>
			<p>
				Cuenta con una interfaz intuitiva y las herramientas de gestión que un comercio necesita para administrar su inventario y sus ventas.
			</p>
			<b-button
			v-b-modal="'miregistrodeventas'"
			class="bg-purple">
				Ver en detalle
			</b-button>
		</div>
	</div>
</template>