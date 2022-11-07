<script>
export default {
    data() {
        return {
            jumboTex: "Questo è un jumbotron"
        }
    }
}
</script>

<template>
    <div class="jumbo">{{jumboTex}}</div>
</template>

<style scoped>

.jumbo{
    width: 100%;
    height: 200px;
    background-color: beige;
    color: red;
}

</style>