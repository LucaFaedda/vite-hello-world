<script >
export default{
    data(){
        return{
            hello: 'La mia prima app con Vite!!!!'
        }
        // potevo scrivere direttamente in h1 il titolo
    }
}

</script>

<template>
<h1>{{ hello }}</h1>


</template>
<style >
h1{
    padding: 60px;
    background-color: rgba(10, 10, 187, 0.521);
    border-radius: 15px;
}
</style>
