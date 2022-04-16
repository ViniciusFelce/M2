<template>
    <div>
        <p>{{txt}}</p>
    </div>
</template>

<script>

    export default {
        name:'PeCont',
        props: {
            txt: String
        }
    }
</script>

<style scoped>
p {
    color: #666666;
}
</style>