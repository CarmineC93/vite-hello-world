<script>
export  {
    data() {
        return {
            title: "La mia prima app con Vite!"
        }
    }
}
</script>

<template>
    <div class="jumbo">{{title}}</div>
</template>

<style scoped>

.jumbo{
    width: 100%;
    height: 200px;
    background-color: beige;
}

</style>