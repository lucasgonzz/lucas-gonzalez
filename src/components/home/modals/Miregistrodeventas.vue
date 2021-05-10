<template>
<b-modal id="miregistrodeventas" body-class="preview" title="Mi Registro de Ventas" hide-footer size="lg">
	<img src="@/assets/miregistrodeventas.png" alt="">
	<div class="specs">
		<p class="title">Especificaciones</p>
		<p>
			Miregistrodeventas es una SPA, es decir, una single-page application, o aplicación de página única, es una aplicación web que cabe en una sola página con el propósito de dar una experiencia más fluida a los usuarios, como si fuera una aplicación de escritorio o de teléfono. Construida con Vue.js trabaja con un API programado en Laravel.
		</p>
		<p>
			Además hace uso de la tecnología PWA, una aplicación web progresiva (PWA por sus siglas en inglés), es un tipo de software que está destinado a funcionar en cualquier plataforma que use un navegador. La funcionalidad incluye trabajar sin conexión, notificaciones y acceso al hardware del dispositivo, lo que permite crear experiencias de usuario como las aplicaciones nativas en dispositivos móviles y de escritorio.
		</p>
		<p class="title">Se maneja a travez de 4 secciones</p>
		<div class="box">
			<p class="title text-purple">INGRESAR</p>
			<p>
				Ingresa nuevos productos a tu inventario completando un formulario con 3 campos obligatorios: nombre, precio y proveedor. Y 5 campos opcionales: códigos de barras, costo, stock, categoría y subcategoria.
			</p>
		</div>
		<div class="box">
			<p class="title text-purple">LISTADO</p>
			<p>
				Mira todos los productos de tu inventario, genera un PDF o exporta un EXEL de tus productos, buscalos por el nombre o filtralos según su precio, fecha de ingreso, categoría, etc.
			</p>
		</div>
		<div class="box">
			<p class="title text-purple">VENTAS</p>
			<p>
				Desde acá vas a ver todas las ventas que hayas hecho en el día, o podes buscar las de una fecha en especifico. También vas a tener disponible la suma de las ventas para hacer un cierre de caja y la suma de los costos de los productos.
			</p>
		</div>
		<div class="box">
			<p class="title text-purple">VENDER</p>
			<p>
				Agrega productos a una nueva venta buscándolos por el nombre o mediante su código de barras. Una vez hayas cargado los productos selecciona un cliente para la venta o guárdala sin mas.
			</p>
		</div>
		<div class="box">
			<p class="title text-purple">EMPLEADOS</p>
			<p>
				Registra tus empleados para darles un perfil personalizado con los permisos que vos les autorices. Por ejemplo: no poder ver las ventas, o solo poder ingresar productos.
			</p>
		</div>
	</div>
</b-modal>
</template>
<style lang="sass">
.text-purple
	color: #4a2c82
</style>
	