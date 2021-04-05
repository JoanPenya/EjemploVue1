<template>
    <div class="prueba">
        <h1>Esto es una demostracion de una pequeña aplicación con vue.js</h1>
    </div>
</template>

<script>
export default {
    name: 'Prueba',
    props: {
        msg: String
    }
}
</script>

<style>
    .prueba{
        position: absolute;
        width: 100%;
        text-align: center;
    }
</style>