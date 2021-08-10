<template>
    <header>
    <img src="https://cdn1.vectorstock.com/i/thumb-large/29/05/tropical-island-logo-line-art-minimalist-symbol-vector-36042905.jpg" alt="beach logo">
    <a href="#">Home</a>
    <a href="#">Gallary</a>
    <a href="#">About Us</a>
    <a href="https://www.inc.com/anne-gherini/how-beach-benefits-your-brain-according-to-science.html" target="_blank"><button>Click to see Article</button></a>
    </header>
</template>

<script>
    export default {
        name : "FirstHeader",
    }
</script>

<style scoped>
img{
    width: 20%;
}
header{
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr 1fr ;
    align-items: center;
}
a{
    text-decoration: none;
    font-size: 1.2rem;
    font-family: 'Handlee', cursive;
}
a:hover{
    color: rgb(128, 168, 226);
    transition: all 0.3s ease 0s;
}
button{
    width: 60%;
    font-size: 1rem;
    font-family: 'Handlee', cursive;
    background-color: mintcream;
    border-radius: 6px;
    padding: 5px;
    color: rgb(161, 111, 46);
    border-color: rgb(161, 111, 46);

}
button:hover{
    background-color: rgb(214, 250, 232);
}
</style>