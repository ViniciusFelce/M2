<template>
<div>
        <div class="cont_H1-Pe">
            <H1Cont :titulo="titulo" />
            <PeCont :txt="txt"/>
        </div>
    <div class="cont">
        <PlanosInter/>
        <PlanosInter2/>
        <PlanosInter3/>
    </div>
    
</div>    
</template>

<script>
    import H1Cont from './H1Cont.vue'
    import PeCont from './PeCont.vue'
    import PlanosInter from './PlanosInter.vue'
    import PlanosInter2 from './PlanosInter2.vue'
    import PlanosInter3 from './PlanosInter3.vue'

    export default {
        name: 'InterContainer',
        components: {
            H1Cont,
            PeCont,
            PlanosInter,
            PlanosInter2,
            PlanosInter3
        },
    data() {
        return {
            titulo: 'Internet',
            txt: 'Selecione um passo de internet para continuar!',
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