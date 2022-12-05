<script>
export default {
  data() {
    return {
      merchandise : [
        {
          url : "buy-comics-digital-comics.png",
          title : "DIGITAL COMICS",
          class : "tablet",
        },
        {
          url : "buy-comics-merchandise.png",
          title : "DC MERCHANDISE",
          class : "maglietta",
        },
        {
          url : "buy-comics-subscriptions.png",
          title : "SUBSCRIPTION",
          class : "carte",
        },
        {
          url : "buy-comics-shop-locator.png",
          title : "COMIC SHOP LOCATOR",
          class : "mappa",
        },
        {
          url : "buy-dc-power-visa.svg",
          title : "DC POWER VISA",
          class : "visa",
        },
        
      ]
    }
  },
}
</script>

<template>
  <section class="section-merchandise">
    <div class="container d-flex justify-content-around align-items-center gap-3 px-3">
      <a v-for="image in merchandise" href="#">
        <img :class="image.class" class="me-2" :src="image.url" alt="">
        {{image.title}}
      </a>
      

    </div>
  </section>


</template>
<style scoped lang="scss">
.section-merchandise{
  background-color: #0282f9;
  padding: 2.5rem 0;
  
  a{
    color: white;
    text-decoration: none;

    img{
      width: 40px;
    }
  }
  .tablet{
    width: 35px;
  }
  .visa{
    width: 47px;
  }
  .carte{
    width: 48px;
  }
  .maglietta{
    width: 45px;
  }
  .mappa{
    width: 30px;
  }
}


</style>