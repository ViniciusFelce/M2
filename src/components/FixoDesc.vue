<template>
<div>
    <label for="item" style="font-size:25px ;">{{tituluFixo}}</label>
    <span class="checkbox">{{valorFixo}}</span>
    <!-- <input id="checkbox" type="checkbox" name="nome"> -->
 <input type="radio" id="" name="Fixo" value="Fixo.id">
</div>
</template>

<script>
    export default {
        name: 'FixoDesc',
            props: {
                tituluFixo: String,
                valorFixo: String
        }
    }
</script>

<style scoped>
div {
    display: flex;
    flex-direction: column;
    align-items: center;
}
span {
    margin: 15px;
}
</style>
