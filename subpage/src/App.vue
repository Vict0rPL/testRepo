<template>

  <div class="row">
    <div class="side col-xl-1 order-1"></div>
  <div id="app" class="container mainContainer col-xl-10 order-2">
    <Navbar/>
    <Introduction/>
    <br>
    <CoverImage/>
    <br>
    <TextArea 
      postTitle="H2. Poppins Bold 24 pt, Line height 36. Letter-spacing 0,2. Do niedawna na stronach WWW korzystało się tylko z Ariala, Timesa i Verdany i trzeba było się modlić."
      textContent="Body text to PT Serif 18 pt, Line height 32. Letter-spacing 0,4. Dominating yet another opponent in yet another final, the United States women’s soccer team claimed its fourth Women’s World Cup title on Sunday, beating the Netherlands, 2-0, in Lyon, France, to repeat as world champions."
     />
    <br>
     <TextSlot>
       <p>Megan Rapinoe and Rose Lavelle <a  href="#" style="color:#2371EF;font-weight:bold;text-decoration: underline;"> a tu jest link bold #2371EF </a> scored second-half goals for the United States, which needed more than an hour to solve a tenacious Netherlands defense but eventually, rush after rush, found a way through. Rapinoe broke the dam with a penalty kick in the 61st minute, and Lavelle sealed the victory with a driving run up the center in the 69th.</p>
     </TextSlot>
    <br>
     <TextArea
      postTitle="Sekcja z przykładowymi obrazkami zacznie się dokładnie tutaj, obrazki są zawsze wyśrodkowane."
      textContent="Szerokość obrazka maksimum wynosi szerokość strony -80 pixeli z prawej i lewej (marginesy). Tak to wygląda jak, zdjęcie w coverze (wyżej). Obrazek jeśli jest mniejszy to nie jest rozciągany. Ma swoja naturalną wilekość, jak poniżej. Padding między tekstem, a obrazkiem to 24 pixele."
     />
    <br>
     <StandaloneImage>
    <br>
      <figure slot=img>
        <img src="./assets/wall.jpg" alt="image">
        <figcaption>Podpis pod obrazkiem, jeśli jest - jest na szerokość obrazka. Poppins Reular 13 pt, Line height 20. Letter-spacing 0,2. A kolor to #111113 ale z opacity / alpha 56% koloru.</figcaption>
      </figure> 
      <br>
     </StandaloneImage>
    <br>
    <TextSlot>
      <p>Padding od obrazka w treści (lub podpisu) do body text to 40 pixeli. Szerokość obrazka maksimum wynosi szerokość strony -80 pixeli z prawej i lewej (marginesy). Tak to wygląda jak, zdjęcie w coverze (wyżej). Obrazek jeśli jest mniejszy to nie jest rozciągany. Ma swoja naturalną wilekość, jak poniżej. Padding między tekstem, a obrazkiem to 24 pixele.</p>
    </TextSlot>
    <br>
    <StandaloneImage>
    <br>
      <figure slot=img>
        <img src="./assets/pixel.jpg" alt="image">
        <figcaption>Podpis pod obrazkiem, jeśli jest - jest na szerokość obrazka. Poppins Reular 13 pt, Line height 20. Letter-spacing 0,2. A kolor to #111113 ale z opacity / alpha 56% koloru.</figcaption>
      </figure> 
    <br>
     </StandaloneImage>
    <br>
     <TextArea
      postTitle="Tutaj sekcja z bulletami i punktatorami, którą planuje dość często używać na blogu, bo uwielbiam wymieniać i porządkować informacje. Musi być git."
      textContent="Poniżej lista bulletpoints, które parametry są dokładnie takie, jak zespecyfikowano poniżej. Lista ta, jak i numeryczna składa się z trzech elementów. Nagłówka/labela dla listy. Oraz samej listy w postaci znacznika i samego tekstu. Bla bla bla."
     />
     <br>
    <ULSquares/>
    <br>
    <TextSlot>
      <p>A lista numeryczna powinna wyglądać, tak, jak poniżej i będzie git. Dzięki :) ,Parametry są dokładnie takie, jak zespecyfikowano poniżej. Lista ta, jak i numeryczna składa się z trzech elementów. Nagłówka/labela dla listy. Oraz samej listy w postaci znacznika i samego tekstu. Bla bla bla.</p>
    </TextSlot>
    <br>
    <OLBold/>
    <br>
    <TextArea
      postTitle="Sekcja, w której pojawia się przykładowy cytat, czyli ostylowanie dla cytatu. Czy jak to zwał." 
      textContent="After the intense four weeks we almost had the whole generator interface system. The whole web app was divided into two spaces for the sake of user experience design. The first space, called Diagram, is where the user constructs a general scheme of the scenario and chooses its necessary elements. The other, called Form, is where the process becomes more detailed and the exact actions connected to particular blocks are created – it is given a name or title and unique parameters and traits."   
    />
    <br>
    <TextSlot>
      <p>Each of those spaces have unique interface, adapted to the user’s needs for both high and low level of details.</p>
    </TextSlot>
    <br>
    <IconQuote/>
    <br>
    <TextArea
      postTitle="A tutaj “link media”, które sobie wymyśliłem, po “wklejeniu linku” - wybranego w CMS. Chciałbym mieć taki styl do wybranych linków." 
      textContent="Będę chciał trochę linkować w artykułach, jako bibliografie pod dany temat, takie linki bym chciał bardziej uwidocznić w treści samego artykułu. Elementy linku są zaciągane z Site title i opisu."   
    />
    <br>
    <CardLink cardTitle="Site title here" cardText="Closing the loop with Design Intelligence" cardLink="www.vkngs.com"><img src="./assets/noise.jpg" class="card-img" alt="image"></CardLink>
 
    <CardLink cardTitle="Digital studio you have been looking for" cardText="We love DIGITAL & we are good at it. We believe that our customers' success is our success. We love to challe […]" cardLink="www.4dmind.com"><img src="./assets/noise.jpg" class="card-img" alt="image"></CardLink>
    <br>
    <TextSlot>
      <h2>Galeria zdjęć. Układ na razie jest mało istotny, jeśli są jakieś gotowce gdzieś do obejrzenia, które możecie podczepić, to dajcie link.</h2>
      <p>TO o czym ja sobie pomyślałem to trzy szpalty zdjęć, na szerokość strony -80 pixeli z lewej i prawej i paddingi po 40 pomiędzy kolumnami. O tak, jak poniżej. Po kliku mamy fullscreen z &lt;&gt;.</p>
    </TextSlot>
    <br>
    <ImageGallery/>
    <br>
    <TextArea
      postTitle="Pora na ostatnie elementy. Share, inne artykuły, stopka." 
      textContent="After the intense four weeks we almost had the whole generator interface system. The whole web app was divided into two spaces for the sake of user experience design. The first space, called Diagram, is where the user constructs a general scheme of the scenario and chooses its necessary elements. The other, called Form, is where the process becomes more detailed and the exact actions connected to particular blocks are created – it is given a name or title and unique parameters and traits."   
    />
    <br>
    <TextSlot>
      <p>Each of those spaces have unique interface, adapted to the user’s needs for both high and low level of details.</p>
    </TextSlot>
    <br>
    <Share/>
    <br>
    <TextSlot>
      <h4 >Warto oblukać</h4>
      <h3>Inni czytali również to:</h3>
      <hr>
    </TextSlot>
    <br>
    <OtherArticles v-bind:mobileCover="true" articleTitle="H2. Poppins Bold 24 pt, Line height 36. Letter-spacing 0,2. To jest tytuł artykułu na listingu" articleDescription="Body text to PT Serif 16 pt, Line height 26. Letter-spacing 0,2. Dominating yet another opponent in yet another final, the United States women’s soccer team claimed its fourth Women’s World Cup title on Sunday, beating the Netherlands, 2-0, in Lyon, France, to repeat as world champions…" >
      <img  slot="imgslot" src="./assets/noise.jpg" class="img-fluid" alt="Responsive image">
      <div slot="leftbottom" class="col" style="textAlign: left;"><i class="fa fa-square green"></i><p class="black" style="display: inline;"><strong>Ćwiczenia</strong></p></div> 
      <div slot="rightbottom" class="col" style="textAlign: right;"><i class="fa fa-spotify green"></i><p class="black" style="display: inline;">Podcast</p></div>   
    </OtherArticles>
    <br> 
    <OtherArticles articleTitle="H2. Poppins Bold 24 pt, Line height 36. Letter-spacing 0,2. To jest tytuł artykułu na listingu" articleDescription="Body text to PT Serif 16 pt, Line height 26. Letter-spacing 0,2. Dominating yet another opponent in yet another final, the United States women’s soccer team claimed its fourth Women’s World Cup title on Sunday, beating the Netherlands, 2-0, in Lyon, France, to repeat as world champions…" >
      <img slot="imgslot" src="./assets/noise.jpg" class="img-fluid" alt="Responsive image">
      <div slot="leftbottom" class="col" style="textAlign: left;"><i class="fa fa-square orange"></i><p class="black" style="display: inline;"><strong >Jak zaczac z UI</strong></p></div> 
      <div slot="rightbottom" class="col" style="textAlign: right;"><p class="black" style="display: inline;">Czytanka na <strong>5 min.</strong></p></div>   
    </OtherArticles>
    <br>
    <TextSlot>
      <h4 >Rozkminy</h4>
      <h3>Zapraszam do dyskusji i rozkmin</h3>
      <hr>
    </TextSlot>
    <br>
    <Comments/>
    <br>
    <Newsletter/>
    <br>
    <Categories/>

  </div>
  <div class=" side col-xl-1 order-3">
  <SideSocial/>
  </div>
  </div>
  
</template>

<script>
import Navbar from './components/Navbar.vue';
import Introduction from './components/Introduction.vue';
import CoverImage from './components/CoverImage.vue';
import TextArea from './components/TextArea.vue';
import TextSlot from './components/TextSlot.vue';
import StandaloneImage from './components/StandaloneImage.vue';
import ULSquares from './components/ULSquares.vue';
import OLBold from './components/OLBold.vue';
import IconQuote from './components/IconQuote.vue';
import CardLink from './components/CardLink.vue';
import ImageGallery from './components/ImageGallery.vue';
import Share from './components/Share.vue';
import OtherArticles from './components/OtherArticles.vue';
import Newsletter from './components/Newsletter.vue';
import Categories from './components/Categories.vue';
import SideSocial from './components/SideSocial.vue';
import Comments from './components/Comments.vue';



export default {
  name: 'App',
  components: {
    Navbar,
    Introduction,
    CoverImage,
    TextArea,
    TextSlot,
    StandaloneImage,
    ULSquares,
    OLBold,
    IconQuote,
    CardLink,
    ImageGallery,
    Share,
    OtherArticles,
    Newsletter,
    Categories,
    SideSocial,
    Comments
  },
  data(){
    return{
      
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  }

  .mainContainer{
    width: 100%;
    padding-bottom: 400px;
  }
  .side{display: none;}

@media (min-width: 1120px){
  .mainContainer {
      width: 90%
  }
  .side{
    display: inline;
    padding: 0px;
  }
  .s{
    background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' width='30' height='30' viewBox='0 0 30 30'%3e%3cpath stroke='rgba(0, 0, 0, 0.5)' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e");
  }
}
</style>
