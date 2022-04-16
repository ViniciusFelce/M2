<template>
<div>
    <label for="item" style="font-size:30px ;">{{tituluTv}}</label>
    <span class="checkbox">{{valorTv}}</span>
    <!-- <input id="checkbox" type="checkbox" name="nome"> -->
 <input type="radio" id="" name="Tv" value="Tv.id">
</div>
</template>

<script>
    export default {
        name: 'TvDesc',
            props: {
                tituluTv: String,
                valorTv: String
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
