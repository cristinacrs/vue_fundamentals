<template>
    <p>Lorem ipsum dolor</p>
    <div>{{text}}</div>
</template>

<script>
    export default{
        data(){
            return {
                text: "Hola!"
            }
        }
    };
</script>

<style>
    p{
        color: plum;
        font-family: sans-serif;
    }
</style>