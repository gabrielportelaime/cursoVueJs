<template>
    <div>
        <h1>Componente App</h1>
        <p>App - Propriedade Style: {{ $style }}</p>
        <topo></topo>
        <conteudo></conteudo>
    </div>
</template>

<script>
import Conteudo from './components/layouts/Conteudo.vue'
import Topo from './components/layouts/Topo.vue'

export default {
    name: 'App',
    components: {
        Conteudo: Conteudo,
        Topo: Topo
    }
}
</script>

<style module>
    h1{
        color: red;
    }
</style>
