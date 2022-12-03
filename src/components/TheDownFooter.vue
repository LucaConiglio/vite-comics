<template>
  <section>
    <div class="container">
      <div class="d-flex justify-content-between align-items-center">
        <div>
          <button class="p-2">SIGN-UP NOW!</button>
        </div>
        <div class="d-flex gap-3 align-items-center">
          <span>FOLLOW US</span>
          <a v-for="image in images" href="#"><img :src="image" alt=""></a>
          
          

        </div>
      
      </div>
    </div>
  </section>
</template>
<script>
export default{
  data () {
    return {
      images : ["footer-facebook.png","footer-twitter.png","footer-youtube.png","footer-pinterest.png","footer-periscope.png",],
    }


  }

}

</script>
<style scoped lang="scss">
section{
  padding: 2rem 0;
  background-color: #303030;
  span{
    color: #0676d6;
    font-weight: 700;
  }

  button{
    color: white;
    font-weight: 600;
    background-color: transparent;
    border: 2px solid #0877de;
  }
}
</style>