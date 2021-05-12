<template>
  <div class="kontakt">

  <v-card>
    <v-responsive :aspect-ratio="16/9">


<div class="info">
    <v-img 
  src="../assets/profilr.png"
  width="50%"
 
  
  ></v-img>
<div class="textbox">
     <div class="text">
      <h2>HVEM ER JEG?</h2>
    </div>

   

      <div class="text">
      <p>Mit navn er Signe Rosenkilde, jeg er 22 år gammel og bor i Gørding med min mand og datter. <br> Jeg læser MULTIMEDIEDESIGN og har en særlig interesse i VISUEL INDENTITET. Min kreativitet trives bedst i en god blanding af struktur og kaos. Strukturen er jeg heldigvis god til selv at skabe. <br> <br> Jeg har meget at byde på, så hvis du har kigget min portfolio, synes jeg du skal scrolle ned og se mit video CV og dowloade mit CV. <br> <br> Jeg vil se frem til at snakke med dig!</p>
    </div>
    <div class="text-center">

 


         <v-btn
    href="mailto:sign5054@easv365.dk"
    download>
        <h2>SEND EMAIL</h2>
        
        
    </v-btn>
    
    </div>
    </div>

  <div class="kontaktinfo">
  <v-btn
    outlined
    href="cv.pdf"
    download>
        <h2>TRYK FOR AT DOWNLOADE CV</h2> 
    </v-btn>

     <div class="video">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/7rjGWcY3gvA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>


  </div>

<div class="icon">
  

    <v-btn
        icon
        href="www.linkedin.com/in/signe-rosenkilde"
        color="grey"
        x-large>
        <v-icon>mdi-linkedin</v-icon>
    </v-btn>
 
</div>
  </div>




   
    </v-responsive>
  </v-card>








  </div>
</template>

<style scoped>

.info{
  width: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  background-image: url("../assets/marble.jpg");
  background-repeat: repeat-y;
}



.textbox{
  width: 50%;
  
  padding-top: 40px;
  
}
.text{
  width: 100%;
  height: fit-content;
  display: flex;
  justify-content: center;
  
}



p{
  padding: 10%;
  text-align: justify;
  line-height: 1.8;
}

@media screen and (max-width: 600px) {
  .textbox {
    width: 100%;
  }
}

.kontaktinfo{
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 40px;
}

.video{
  display: flex;
  justify-content: center;
  padding-top: 100px;
  
}

.icon{
 margin-left: auto;
 padding: 10px;
}
</style>

<script>

</script>
