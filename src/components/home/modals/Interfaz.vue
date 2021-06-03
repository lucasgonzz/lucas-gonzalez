<template>
<b-modal id="interfaz" body-class="preview" title="Interfaz" hide-footer size="lg">
	<img src="@/assets/interfaz.png" alt="">
	<div class="specs">
		<p class="main-title">Especificaciones</p>
		<p>
			Esta app se conecta mediante la api de Wordpress a una tienda construida en esta plataforma. La tienda funciona en Buenos Aires y Rosario, cada ciudad con su propia tienda, por lo que toma los pedidos de ambas ciudades y los enlista de manera separada.
		</p>
		<p class="main-title">Se manejan los siguientes recursos</p>
		<div class="box">
			<p class="title text-purple">EMPLEADOS</p>
			<p>
				Se ingresan nuevos empleados y se les asignan sus roles dentro de la empresa, dándoles de esta manera una cuenta para ingresar al sistema con sus respectivos permisos.
			</p>
		</div>
		<div class="box">
			<p class="title text-purple">ZONAS DE ENVIO</p>
			<p>
				Se ingresan las zonas de envio correspondientes a cada ciudad para luego asignarcelas a los pedidos que lleguen de Wordpress.
			</p>
		</div>
		<div class="box">
			<p class="title text-purple">PEDIDOS</p>
			<p>
				Se listan todos los pedidos del día corriente en base a la sucursal seleccionada.
			</p>
			<p>
				Los empleados que tengan permisos para manipular los pedidos van a poder asignarle a cada uno una zona de envió, un armador y un repartidor, de esta manera cuando ingrese un empleado con el rol de repartidor va a tener listado los pedidos que le hayan sido asignados.
			</p>
			<p>
				También tienen la opción de generar una boleta con los datos del pedido seleccionado.
			</p>
		</div>
	</div>
</b-modal>
</template>
	