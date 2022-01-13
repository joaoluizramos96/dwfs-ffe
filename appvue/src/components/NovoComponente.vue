<template>
<!-- HTML -->
    <div>
        <h1>{{ texto }}</h1>
        <p> {{ texto }} </p>
    </div>
</template>


<script>
    export default{
        name: 'NovoComponente',
        props: {
            texto: String
        }
    }
</script>

<style scoped>
    h1 {
        color: red;
    }
</style>