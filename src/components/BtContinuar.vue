<template>
<div>
    <a href=""><button @click="$emit('ativarFixo')">Continuar</button></a>
</div>    
</template>

<script>
export default {
    name: 'BtContinuar',
    emits: ['ativarFixo']
}
</script>

<style scoped>
    button {
        margin-left: 2%;
        background-color: #7e7d7d;
        color: rgb(199, 199, 199);
        border: none;
        height: 50px;
        width: 200px;
        border-radius: 5px;
        cursor: pointer;
        margin-bottom: 3%;
    }
</style>
