<template>
  <div class="home">
  
       

  <v-carousel
  cycle
  show-arrows-on-hover
  >
    
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
      
    ></v-carousel-item>
  </v-carousel>


  </div>
</template>

<style>

.home{
  margin-bottom: 50px;
}

</style>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: require('../assets/mockupapp.png'),
          },
          {
            src: require('../assets/mockupkomp.png'),
          },
          {
            src: require('../assets/mockupvand.png'),
          },
          {
            src: require('../assets/plakat1.png'),
          },
        ],
      }
    },
  }
</script>