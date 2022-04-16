<template>
    <div class="contFixo">
        <FixoDesc :tituluFixo="tituluFixo" :valorFixo="valorFixo"/> 
    </div>
</template>

<script>
import FixoDesc from './FixoDesc.vue'
export default {
  components: { FixoDesc },
    name: 'PlanosFixo',
        data() {
        return {
            tituluFixo: 'Ilimitado Fixo brasil',
            valorFixo: 'R$ 50,00'
        }
    }
}
</script>

<style scoped>
    .contFixo {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        width: 30vh;
        height: 200px;
        margin-bottom: 3%;
        box-shadow: rgba(0, 0, 0, 0.3) 0px 19px 38px, rgba(0, 0, 0, 0.22) 0px 15px 12px;
    }
</style>