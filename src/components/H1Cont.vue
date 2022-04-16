<template>
    <div>
        <h1>{{titulo}}</h1>
    </div>
</template>

<script>

    export default {
        name:'H1Cont',
        props: {
            titulo: String
        }
    }
</script>

<style scoped>
h1 {
    color: #8c3eae;
}
</style>