<template>
	<b-row>
		<b-col
		sm="8">
			<p class="main-title">
				Habilidades principales
			</p> 
			<div class="projects">
				<div class="box bg-warning">
					<i class="icon-checkbox-checked"></i>
					Javascript
				</div>
				<div class="box bg-success text-white">
					<i class="icon-checkbox-checked"></i>
					Vue.js
				</div>
				<div class="box bg-primary text-white">
					<i class="icon-checkbox-checked"></i>
					PHP
				</div>
				<div class="box bg-danger text-white">
					<i class="icon-checkbox-checked"></i>
					Laravel
				</div>
			</div>
		</b-col>
	</b-row>
</template>
<style scoped lang="sass">
.row 
	justify-content: center
.box
	width: 150px
	text-align: center
	[class^='icon-']:before
		display: block
</style>