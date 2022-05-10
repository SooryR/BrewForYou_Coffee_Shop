<template>
<div class="About_us">
    <head>
        <meta charset=”utf-8” />
        <title>BrewForYou</title>
        <link rel="stylesheet" href="./style_Sheets/about_us_style.css">
    </head>
    <NavBar/>

    <body>
        <h1 class="title">About us</h1>
        <div class="body1">
            <h1>How we get our coffee</h1>
            <p>We get shipments of coffee beans from Brazil, Colombia, Vietnam, and Indonesia. We make sure that all the workers of the plantations that farm coffee beans are rightly treated and they focus on quality over quantity. </p>
            <div class="farm_Info">
                <a href="https://brazilianfarmers.com/coffee/">More info on Brazilian farms</a>
                <a href="https://www.coffeehunter.com/coffee-country/vietnam/">More info on Vietnam farms</a>
                <a href="https://www.nomadcoffeeclub.com/pages/colombia">More info on Colombia farms</a>
            </div>
            <img src="../assets/images/outline-world-map.png" alt="" width="41%">
            <img src="../assets/images/coffee-fields.png" alt="" width="46%">
        </div>
        <div class="body2">
            <h1>What we have planned for the future</h1>
            <p>We plan to add desserts that have a coffee flavor as options to choose from our menu. Some examples are coffee ice cream, chocolate, cake, and so on.</p>
            <p>In the near future, we are going to expand out and put more store locations in the Canada Ontario region.</p>
            <img src="../assets/images/future.jpg" alt="" height="400px" width="100%">
        </div>
        <div class="body3">
            <h1>How to make our Black Coffee</h1>
            <ol type="1">
                <li>Each coffee bean is checked for any deformities then is roasted to perfection and ground up to a mix of fine-grained and rough to get the strongest coffee flavour without the bitterness.</li>
                <li>Coldwater is filtered as the tap water has other minerals and chemicals that affect the flavour.</li>
                <li>Measured 2 tablespoons of our ground coffee for every 6 ounces or 3/4 cup of water. </li>
                <li>Water temperature is heated to between 90 degrees - 95 degrees celsius. We don't boil the water because it can cause the coffee ground to extract too much too early, leaving a bitter taste in your cup.</li>
                <li>Rinse filter paper with hot water before brewing. Use a good quality oxygen bleached filter.</li>
                <li>Pour just enough water over the grounds to get them wet and not soaked, to let them bloom.</li>
                <li>After 30-45 seconds continue the pour-over and wait for 5 mins. Then serve.</li>
            </ol>
        </div>
        <video class="body4" src="../assets/video/How-to-Make-Your-Best-Coffee-Ever.mp4" controls></video>
    </body>
    <Footer/>
</div>
</template>

<script>
import Footer from './Footer.vue'
import NavBar from './NavBar.vue'

export default {
  components: {
    Footer,
    NavBar
  },
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped src="../assets/style_Sheets/about_us_style.css">
</style>
