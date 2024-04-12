<template>
    <div>
        <h1>Componente Conteúdo</h1>
        <p>Conteudo - Propriedade Style: {{ $style }}</p>
        <div class="teste-1">Class teste-1</div>
        <div id="teste-2">ID teste-2</div>
        <home></home>
        <publicar-vaga></publicar-vaga>
    </div>
</template>

<script>
    import Home from '../views/Home.vue'
    import PublicarVaga from '../views/PublicarVaga.vue'

    export default{
        name: 'Conteudo',
        components: {
            Home,
            PublicarVaga
        }
    }
</script>

<style module>
    h1{
        color: green;
    }
    .teste-1{
        background-color: red;
    }
    #teste-2{
        background-color: yellow;
    }
</style>