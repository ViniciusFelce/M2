<template>

<div class="sectionPedido" style="box-shadow: rgba(0, 0, 0, 0.56) 0px 22px 70px 4px;">
    <div class="istalacao">
        <p>Total de isntalação</p> <p>Grátis!</p>
    </div>
    <div class="total">
        <span>Total:</span> <span>R$ 0,00/Mês</span>
    </div>
    <BtContinuar/>
</div>
</template>

<script>
    import BtContinuar from './BtContinuar.vue'
    export default {
        components: { BtContinuar },
        name:'Pedido'
    }
</script>

<style scoped>
    .istalacao {
        display: flex;
        justify-content: space-between;
    }
    .istalacao {
        color: #666666;
        font-size: 20px;
    }
    .total{
        display: flex;
        justify-content: space-between;
    }
    .total * {
            color: #8c3eae;
            font-size: 30px;
    }
    .sectionPedido * {
        margin: 2%;
    }
    
</style>
