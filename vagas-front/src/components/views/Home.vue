<template>
    <div>
        <h1>Componente Home</h1>
        <p>Home - Propriedade Style: {{ $style }}</p>
    </div>
</template>

<script>
    export default{
        name: 'Home'
    }
</script>

<style module>
    h1{
        color: blue;
    }
</style>