<template>
	<div>
		<h1>Componente Olá {{ variavel }}</h1>
		<p>URL da API: {{ url_api }}</p>
		<p>
			Modo: {{ modo }}
		</p>
	</div>
</template>

<script>
export default {
	name: 'HelloWorld',
	data: () => ({
			variavel: process.env.VUE_APP_MINHA_VARIAVEL_AMBIENTE,
			url_api: process.env.VUE_APP_API_URL,
			modo: process.env.VUE_APP_MODO
		})
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

</style>
