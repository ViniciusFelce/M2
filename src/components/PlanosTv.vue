<template>
    <div class="contTv">
        <TvDesc :tituluTv="tituluTv" :valorTv="valorTv"/> 
    </div>
</template>

<script>
import TvDesc from './TvDesc.vue'
export default {
  components: { TvDesc },
    name: 'PlanosTv',
        data() {
        return {
            tituluTv: 'Ultimate HD',
            valorTv: 'R$ 120,00'
        }
    }
}
</script>

<style scoped>
    .contTv {
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