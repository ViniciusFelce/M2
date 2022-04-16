<template>
<div>
    <div class="cont_H1-Pe">
        <H1Cont :titulo="titulo" />
        <PeCont :txt="txt"/>
    </div>
    <div class="cont">
        <PlanosTv/>
        <PlanosTv2/>
    </div>
</div>    
</template>

<script>
    import H1Cont from './H1Cont.vue'
    import PeCont from './PeCont.vue'
    import PlanosTv from './PlanosTv.vue'
    import PlanosTv2 from './PlanosTv2.vue'

    export default {
        name: 'TvContainer',
        components: {
            H1Cont,
            PeCont,
            PlanosTv,
            PlanosTv2
        },
    data() {
        return {
            titulo: 'Tv',
            txt: 'Selecione um passo de Tv para continuar!'
            }
        }
    }
    
</script>

<style scoped>
    .cont {

        margin-bottom: 3%;
        display: flex;
        align-items: center;
        justify-content: space-evenly;
        flex-wrap: wrap;
        
    }
    .cont_H1-Pe {
        display: flex;
        flex-direction: column;
        margin-left: 9%;
    }
</style>