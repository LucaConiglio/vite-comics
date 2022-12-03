<template>
  <header>
    <div class="container m-auto">
      <nav class="d-flex justify-content-between align-items-center">
        <div>
          <img src="dc-logo.png" alt="">
        </div>
        <div class="d-flex gap-4">
          <a v-for="links in linkHeader" href="#">{{links}}</a>
          
        </div>

      </nav>
    </div>
  </header>
    
  
</template>

<script>
export default {
  data() {
    return {
      linkHeader : ["CHARACTERS","COMICS","MOVIES","TV,GAMES","COLLECTIBLES","VIDEOS","FANS","NEWS","SHOP"],
    }
  },
  
}
</script>

<style scoped lang="scss">

header{
  padding: 1.8rem 0;
  img{
    width: 90px;
  }

  a {
    text-decoration: none;
    color: black;
    font-weight: 500;

    &:hover {
      color: blue;
    }
  }
}
  
</style>