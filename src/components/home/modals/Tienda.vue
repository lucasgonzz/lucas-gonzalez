<template>
<b-modal id="tienda" body-class="preview" title="Tienda" hide-footer size="lg">
	<img src="@/assets/tienda.jpg" alt="">
	<div class="specs">
		<p class="title">Especificaciones</p>
		<p>
			Esta tienda virtual funciona de manera sincronizada con miregistrodeventas.com
		</p>
		<p>
			Cada usuario de miregistrodeventas puede tener una tienda funcionando bajo un dominio con el nombre de su negocio.  
		</p>
		<p>
			En la tienda se podran ver todos los artículos que tengan asigandos una foto y que tengan unidades en stock.
		</p>
		<p>
			A continuacion, se presenta un caso de uso para un usuario de miregistrodeventas, cuyo nombre del negocio es "kiosco verde", la tienda funciona en <a class="btn-link" href="https://kioscoverde.com" target="_blank">aquí</a>.
		</p>
		<p class="title">La componen las siguientes páginas</p>
		<div class="box">
			<p class="title text-success">INICIO</p>
			<p>
				Esta es la página principal, donde se listan los artículos destacados, previamente seleccionados en miregistrodeventas por el negocio, o los artículos de la categoria que se seleccione.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">PÁGINA DEL ARTÍCULO</p>
			<p>
				Muestra en detalle los datos del artículo que se haya seleccionado desde el INICIO, con la opcion de ver los distintos modelos del artículo, un boton para agregarlo a favoritos y otro para agregarlo al carrito.
			</p>
			<p>
				En la parte intermedia se mostraran algunos artículos relacionados con el seleccionado por el usuario.
			</p>
			<p>
				El usuario tambien va a tener disponible un formulario para hacer una pregunta sobre ese artículo al negocio. Cuando el negocio responda a la pregunta, esta se listara junto con las demas preguntas de ese artículo al final de la página.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">FAVORITOS</p>
			<p>
				Se listan todos los artículos que el usuario haya marcado como favoritos, para un rapido acceso a la PÁGINA DEL ARTÍCULO con los datos del artículo favorito seleccionado.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">PREGUNTAS</p>
			<p>
				Se listan todos los artículos en los que el usuario haya hecho una pregunta y el negocio haya respondido, para un rapido acceso a la PÁGINA DEL ARTÍCULO con los datos del artículo y sus preguntas.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">COMPRAS</p>
			<p>
				Se listan todas las compras que haya hecho el usuario, con la posibilidad de ver los artículos que componen cada una.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">CARRITO</p>
			<p>
				La página mas importante de un tienda, en la página del carrito el usuario va a ver listados todos los artículos que haya seleccionado para hacer un pedido. Con la opcion para retirar el pedido por el local, o para ingresar una direccion y que se lo envien a domicilio.
				Despues de seleccionar como quiere retirar el pedido, se le preguntara como desea pagar, si en efectivo o con tarjeta. En caso de seleccionar con tarjeta, se pediran los datos de la misma.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">NOTIFICACIONES</p>
			<p>
				En esta página el usuario va poder ver las notificaciones referentes a:
			</p>
			<p class="item">Actualizaciones en el estado del pedido actual</p>
			<p class="item">Informes sobre respuestas a sus preguntas</p>
			<p class="item">Informes sobre los pagos del pedido, informando el correcto cobro del pedido, o por el contrario informando del error al momento de hacer el cobro</p>
		</div>
		<p class="title">Caracteristicas</p>
		<div class="box">
			<p class="title text-success">COBROS CON TARJETA</p>
			<p>
				Los cobros con tarjeta de credito funcionan gracias a la integracion con mercadopago. La integracion se hizo con la api de mercadopago, siendo esta opcion la mas compleja de llevar a cabo, dando ventajas significativas como el hecho de poder realizar la toma de datos de la tarjeta dentro de la tienda, sin que el usuario tenga que salir en ningun momento de nuestra página.
			</p>
			<p>
				Los datos obtenidos se almacenan para ser procesados una vez que el negocio confirma la disponibilidad de los artículos del pedido. 
			</p>
		</div>
		<div class="box">
			<p class="title text-success">NOTIFICACIONES</p>
			<p>
				Las notificaciones para los usuarios son almacenadas en la base de datos y mostradas en la página NOTIFICACIONES. Ademas se envian notificaciones push a sus telefonos y computadoras para notificarlos cuando no estan usando la aplicacion.
			</p>
			<p>
				De esta forma se los mantiene al tanto de actualizaciones en sus compras y otros eventos.
			</p>
		</div>
	</div>
</b-modal>
</template>
	