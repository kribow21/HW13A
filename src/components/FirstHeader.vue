<template>
    <header>
    <img src="https://cdn1.vectorstock.com/i/thumb-large/29/05/tropical-island-logo-line-art-minimalist-symbol-vector-36042905.jpg" alt="beach logo">
    <a href="#">Home</a>
    <a href="#">Gallary</a>
    <a href="#">About Us</a>
    <button>Click for Article</button>
    </header>
</template>

<script>
    export default {
        name : "FirstHeader"
    }
</script>

<style scoped>
img{
    width: 20%;
}
header{
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr 1fr ;
    background-color: rgb(184, 240, 240);
    align-items: center;
}
a{
    text-decoration: none;
    font-size: 1.2rem;
    font-family: 'Handlee', cursive;
}
button{
    width: 60%;
    font-size: 1rem;
    font-family: 'Handlee', cursive;

}
</style>