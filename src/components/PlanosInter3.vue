<template>
    <div class="contInter">
        <interDesc :tituluInter="tituluInter" :valorInter="valorInter"/> 
    </div>
</template>

<script>
import InterDesc from './InterDesc.vue'
export default {
  components: { InterDesc },
    name: 'PlanosInter',
        data() {
        return {
            tituluInter: '300MB',
            valorInter: 'R$ 79,00'
        }
    }
}
</script>

<style scoped>
    .contInter {
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
