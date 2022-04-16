<template>
<div>
    <label for="item" style="font-size:30px ;">{{tituluInter}}</label>
    <span class="checkbox">{{valorInter}}</span>
    <!-- <input id="checkbox" type="checkbox" name="nome"> -->
 <input type="radio" id="" name="Internet" value="Internet.id">
</div>
</template>

<script>
    export default {
        name: 'InterDesc',
            props: {
                tituluInter: String,
                valorInter: String
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
