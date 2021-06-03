<template>
<b-modal id="tienda" body-class="preview" title="Tienda" hide-footer size="lg">
	<img src="@/assets/tienda.jpg" alt="">
	<div class="specs">
		<p class="main-title">Especificaciones</p>
		<p>
			Esta tienda virtual funciona de manera sincronizada con miregistrodeventas.com
		</p>
		<p>
			Cada usuario de Miregistrodeventas puede tener una tienda funcionando bajo un dominio con el nombre de su negocio.  
		</p>
		<p>
			En la tienda se podrán ver todos los artículos que tengan asignados al menos una foto y que tengan unidades en stock.
		</p>
		<p class="main-title">La componen las siguientes páginas</p>
		<div class="box">
			<p class="title text-success">INICIO</p>
			<p>
				Esta es la página principal, donde se listan los artículos destacados, previamente seleccionados en miregistrodeventas por el negocio, o los artículos de la categoría que el cliente seleccione.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">PÁGINA DEL ARTÍCULO</p>
			<p>
				Muestra en detalle los datos del artículo que se haya seleccionado desde el INICIO, con la opción de ver los distintos modelos del artículo, un botón para agregarlo a favoritos y otro para agregarlo al carrito.
			</p>
			<p>
				En la parte intermedia se mostraran algunos artículos relacionados con el seleccionado por el usuario.
			</p>
			<p>
				El usuario también va a tener disponible un formulario para hacer una pregunta sobre ese artículo al negocio. Cuando el negocio responda a la pregunta, esta se listara junto con las demás preguntas de ese artículo al final de la página.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">FAVORITOS</p>
			<p>
				Se listan todos los artículos que el usuario haya marcado como favoritos, para un rápido acceso a la PÁGINA DEL ARTÍCULO con los datos del artículo favorito seleccionado.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">PREGUNTAS</p>
			<p>
				Se listan todos los artículos en los que el usuario haya hecho una pregunta y el negocio haya respondido, para un rápido acceso a la PÁGINA DEL ARTÍCULO con los datos del artículo y sus preguntas.
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
				La página mas importante de un tienda, en la página del carrito el usuario va a ver listados todos los artículos que haya seleccionado para hacer un pedido. 
			</p>
			<p>
				Con la opción para retirar el pedido por el local, o para ingresar una dirección y que se lo envíen a domicilio.
				Despues de seleccionar como quiere retirar el pedido, se le preguntara como desea pagar, si en efectivo o con tarjeta. En caso de seleccionar con tarjeta, se pedirán los datos de la misma.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">NOTIFICACIONES</p>
			<p>
				En esta página el usuario va poder ver las notificaciones referentes a:
			</p>
			<p class="item">
				<i class="icon-hand-o-right"></i>
				Actualizaciones en el estado del pedido actual.
			</p>
			<p class="item">
				<i class="icon-hand-o-right"></i>
				Informes sobre respuestas a sus preguntas.
			</p>
			<p class="item">
				<i class="icon-hand-o-right"></i>
				Informes sobre los pagos del pedido, informando el correcto cobro del mismo, o por el contrario, informando sobre un error al momento de hacer el cobro.
			</p>
		</div>
		<p class="main-title">Pasos para manejar los pedidos</p>
		<div class="box">
			<p class="title text-success">Confirmación</p>
			<p>
				En este primer paso, el negocio recibe el pedido, y verifica la disponibilidad de stock de los artículos del pedido. Luego hay dos opciones:
			</p>
			<p>
				<i class="icon-hand-o-right"></i>
				En caso de haber un problema, cancelar el pedido, seleccionando los artículos faltantes, o detallando el problema por el cual no se puede cumplir con el mismo. Seguido a esto se enviara una notificación al usuario para que actualice el pedido.
			</p>
			<p>
				<i class="icon-hand-o-right"></i>
				Si por el contrario no hay problema, el negocio confirma el pedido. Si la forma de pago es con tarjeta, en este punto, luego de ser confirmado, se procesa el pago.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">Listo para retirar</p>
			<p>
				Una vez confirmado el pedido, el negocio tiene que armarlo. Cuando el negocio indique que ya esta listo, se enviara una notificación al cliente informando que ya puede retirarlo, o en el caso que haya seleccionado que se lo envíen, se le informara que el repartidor esta próximo a salir. 
			</p>
		</div>
		<div class="box">
			<p class="title text-success">Entregado</p>
			<p>
				Cuando el cliente ya paso a buscar el pedido, o cuando el repartidor ya hizo entrega del mismo, el negocio lo marca como entregado, de esta manera se limpia el pedido de la bandeja de entrada del negocio, y se guarda la venta junto a las demás que haya hecho en el negocio, para sincronizar el pedido con las ventas del negocio.
			</p>
		</div>
		<p class="main-title">Características</p>
		<div class="box">
			<p class="title text-success">COBROS CON TARJETA</p>
			<p>
				Los cobros con tarjeta de crédito funcionan gracias a la integración con Mercadopago. La integración se hizo con la api de Mercadopago, siendo esta opción la mas compleja de llevar a cabo, dando ventajas significativas como el hecho de poder realizar la toma de datos de la tarjeta dentro de la tienda, sin que el usuario tenga que salir en ningún momento de nuestra página.
			</p>
			<p>
				Los datos obtenidos son almacenados, para ser procesados una vez que el negocio confirma la disponibilidad de los artículos del pedido. Esto es de suma importancia, ya que podemos realizar el cobro del pago cuando se pertinente al haber almacenado los datos de las tarjeta.
			</p>
			<p>
				IMPORTANTE
			</p>
			<p>
				<i class="icon-hand-o-right"></i>
				Los datos de la tarjeta no son almacenados en nuestros servidores, ya que incumpliría las normas de Mercadopago.
			</p>
			<p>
				<i class="icon-hand-o-right"></i>
				Al haber realizado la interacción con la api de Mercadopago, nosotros recibimos un token (una cadena de caracteres única para identificar una transacción), para que con ese token y los datos del pedido (total a cobrar, cantidad de cuotas, etc) dispongamos cuando realizar el cobro del mismo.
			</p>
		</div>
		<div class="box">
			<p class="title text-success">NOTIFICACIONES</p>
			<p>
				Las notificaciones para los usuarios son almacenadas en la base de datos y mostradas en la página NOTIFICACIONES.
			</p>
			<p> 
				Además se envían notificaciones push a sus teléfonos y computadoras para notificarlos cuando no estén usando la aplicación de manera activa, por ejemplo, las notificaciones que recibimos de whatsapp en la barra de notificaciones. De esta forma se los mantiene al tanto de actualizaciones en sus compras y otros eventos.
			</p>
		</div>
		<p class="main-title">Casos de uso</p>
		<div class="box">
			<p class="title text-success">KIOSCO VERDE</p>
			<p>
				En este caso, la tienda online fue puesta en marcha para una juguetería de Entre Ríos.
			</p>
			<p>
				Esta juguetería ya contaba con una cuenta de Miregistrodeventas, que es de donde la tienda toma los datos para mostrarlos al publico.
			</p>
			<p>
				La tienda esta funcionando <a class="btn-link" href="https://kioscoverde.com" target="_blank">aquí</a>.
			</p>
		</div>
	</div>
</b-modal>
</template>
	