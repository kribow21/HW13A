<template>
    <header>
    <img src="https://images.theconversation.com/files/370685/original/file-20201123-13-x1rq79.jpg" alt="beach pineapple">
    <a href="">Home</a>
    <a href="">Gallary</a>
    <a href="">About Us</a>
    </header>
</template>

<script>
    export default {
        name : "FirstHeader"
    }
</script>

<style scoped>
img{
    width: 30%;
}
header{
    display: grid;
    grid-template-columns: repeat(4 , 0.5fr);
    background-color: rgb(184, 240, 240);
}
</style>