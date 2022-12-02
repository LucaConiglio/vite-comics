<template>
  <section>
    <div class="container">
      <div class="row">
        <div class="col-6 pt-4 pb-5">
          <div class="container d-flex gap-4">
            <div class="d-flex flex-column">
              <h4 class="py-2">DC COMICS</h4>
              <a v-for="link in dcComics" href="#">{{link}}</a>
              <h4 class="pt-3 pb-2">SHOP</h4>
              <a v-for="link in shop" href="#">{{link}}</a>
            </div>

            <div class="d-flex flex-column">
              <h4 class="py-2">DC</h4>
              <a v-for="link in dc" href="#">{{link}}</a>
            </div>

            <div class="d-flex flex-column">
              <h4 class="py-2">SITES</h4>
              <a v-for="link in sites" href="#">{{link}}</a>
            </div>



          </div>
        </div>
        <div class="col-6 logo">
          
        </div>
      </div>
    </div>
  </section>
  <SignUpFooter></SignUpFooter>
</template>
<script>


export default {
    data() {
        return {
            dcComics: ["Characters", "Comics", "Movies", "TV", "Games", "Videos", "News"],
            shop: ["Shop DC", "Shop DC Collectibles"],
            dc: ["Terms Of Use", "Privacy Policy (News)", "Ad Choices", "Advertising", "Jobs", "Subscriptions", "Talent Workshops", "CPSC Certificates", "Ratings", "Shop Help", "Contacs Us"],
            sites: ["DC", "MAD Magazine", "DC Kids", "DC Universe", "DC Power Visa"]
        };
    },
}
</script>

<style scoped lang="scss">
section{
  background-image: url("footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  color: white;

  a{
    text-decoration: none;
    color: rgb(137, 137, 137);
    font-size: medium;
  }
  
  .logo{
    background-image: url("dc-logo-bg.png");

    background-repeat: no-repeat;
    background-position: center;
    background-position: right;
    
  }
}
</style>