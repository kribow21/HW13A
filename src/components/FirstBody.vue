<template>
    <body>
    <FirstHeader></FirstHeader>
        <h1>How the beach benefits your brain according to science</h1>
        <section>
            <img src="https://images.pexels.com/photos/2425664/pexels-photo-2425664.jpeg" alt="">
            <img src="https://images.pexels.com/photos/1680140/pexels-photo-1680140.jpeg" alt="">
            <img src="https://images.pexels.com/photos/2645245/pexels-photo-2645245.jpeg" alt="">
        </section>
        <article>
            <div>
                <h3>Remove the blues</h3>
                <p>Studies have shown that different colors often produce different psychological, emotional, and physical effects. The color blue, for instance, is often used in marketing material to convey a sense of calmness.
                The Global Healing Center advises individuals to actually surround themselves in blue as a way to reduce stress. 
                According to Richard Shuster, PsyD, clinical psychologist, he agrees that blue has a profound calming effect on people.
                "Staring at the ocean actually changes our brain waves' frequency and puts us into a mild meditative state," says Shuster. </p>
            </div>
            <div>
                <h3>Smell the ocean mist</h3>
                <p>When you first step out on the sand and allow your lungs to be filled with salty misty air, your brain may be receiving instant benefits. The negative ions (oxygen ions with an extra electron attached, produced via water molecules) in the ocean air can actually help calm your brain.
                Negative ions have been shown to have a pronounced anti-depressant effect as well. As early as 1932, American research engineer Dr. Clarence Hansell noticed that the mood of one of his colleagues fluctuated in response to the type of ions - cheerful when subjected to positive ions and gloomy when subjected to negative ones.
                Subsequent studies have found that the act of negatively ionized air -- the kind you receive when you get outside for a gulp of fresh air -- can alleviate symptoms of seasonal affective disorder (SAD).  </p>
            </div>
            <div>
                <h3>Feel the sand between your toes</h3>
                <p>Grounding, otherwise known as walking barefoot, has been proven to have a number of stimulating benefits to our bodies and minds. 
                The reason is that our feet contain a rich network of nerves and acupuncture points. Our feet are able to absorb free ions on the earth surface in much the same way that our lungs are able to absorb ions in the air.
                A report in the Journal of Alternative and Complementary Medicine shed some more light on these benefits. The earth is negatively charged, so when you walk barefoot, you're connecting your body to a negatively charged supply of energy. 
                The result is one that many of us feel as soon as we kick off our shoes. 
                Walking barefoot on the beach can trigger tingling warm sensations produced as a result of us "grounding" to earth.</p>
            </div>
        </article>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Handlee&family=Raleway&display=swap" rel="stylesheet">
    <TestComp></TestComp>
    <FirstFooter></FirstFooter>

    </body>
</template>

<script>
import FirstHeader from './FirstHeader.vue'
import FirstFooter from './FirstFooter.vue'
import TestComp from './TestComp.vue'

    export default {
        name : "FirstBody",
        components : {
            FirstHeader,
            FirstFooter,
            TestComp
        }
    }
</script>

<style scoped>
@keyframes gradient {
    0% {
        background-position: 0% 50%;
    }
    50% {
        background-position: 80% 50%;
    }
    100% {
        background-position: 0% 50%;
    }
}
*{
    padding: 0;
    margin: 0;
    background: linear-gradient(-40deg, #52cfee, #d1fcff, #a6ffff, #6ac9f5);
    background-size: 400% 400%;
    animation: gradient 12s ease infinite;
}
article{
    display: grid;
    grid-template-rows: auto;
    margin: 5% 10%;
}
h1{
    margin-left: 15%;
    font-size: 3rem;
    font-family: 'Handlee', cursive;
    padding: 3%;
    color: rgb(60, 84, 219);
}
h3{
    font-family: 'Handlee', cursive;
    font-size: 2rem;
    color: rgb(207, 162, 103);


}
p{
    font-family: 'Raleway', sans-serif;
    line-height: 1.6;
    font-size: 1.2rem;
    color: rgb(161, 111, 46);
    padding-bottom: 4%;

}
section{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    margin-left: 4%;
}
img{
    width: 400px;
}

</style>