<template>
<div class="app">
  <v-app>
     <v-parallax
    dark
    height="3000px"
    
  >  
   
       <v-app-bar
      app
      height="120"
      color="#ffffff"
      light
      hide-on-scroll
      
      
    >

      <v-spacer></v-spacer>


        <div class="d-flex align-center">
       

        <v-img
          alt="Vuetify Name"
          
          contain
          min-width="300"
          src="https://i.ibb.co/Qb7GnPq/logo.png"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

       <template v-slot:extension>
        <v-tabs 
        align-with-title 
        color="grey lighten-2"
        >
          <v-spacer></v-spacer>
          <v-tab>
            <router-link to="/Home" > <h3>FORSIDE</h3> </router-link>
          </v-tab>
          <v-spacer></v-spacer>
          
           <v-tab>
            <router-link to="/portfolio" > <h3>PORTFOLIO</h3> </router-link>
          </v-tab>
         
          <v-spacer></v-spacer>
          
           <v-tab>
            <router-link to="/Kontakt" > <h3>OM</h3> </router-link>
          </v-tab>
          
          <v-spacer></v-spacer>
        </v-tabs>
      </template>
      
    </v-app-bar>
  
     <v-main>
      

    <router-view />
    </v-main>
</v-parallax>
  </v-app>
  </div>
</template>

<style>

h1, h2, h3, p{
  font-family: sweet-sans-pro,sans-serif;
  font-weight: 300;
  color: black;
}

a{
  text-decoration:none;
  font-family: sweet-sans-pro,sans-serif;
  font-weight: 300;
  font-style: normal;
  color: black;
}

.app{
  margin-top: 40px;
}




</style>

<script>
 


</script>
