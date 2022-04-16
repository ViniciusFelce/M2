<template >
<div>
    <div class="cont_H1-Pe">
        <H1Cont :titulo="titulo" />
        <PeCont :txt="txt"/>
    </div>
    <div class="cont">
        <PlanosFixo/>
    </div>
</div>    
</template>

<script>
    import H1Cont from './H1Cont.vue'
    import PeCont from './PeCont.vue'
    import PlanosFixo from './PlanosFixo.vue'

    export default {
        name: 'FixoContainer',
        components: {
            H1Cont,
            PeCont,
            PlanosFixo
        },
    data() {
        return {
            titulo: 'Fixo',
            txt: 'Selecione um passo de fixo para continuar!'
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