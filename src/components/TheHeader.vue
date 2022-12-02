<template>
  <header>
    <div class="container m-auto">
      <nav class="d-flex justify-content-between align-items-center">
        <div>
          <img src="dc-logo.png" alt="">
        </div>
        <div class="d-flex gap-4">
          <a href="#">CHARACTERS</a>
          <a href="#">COMICS</a>
          <a href="#">MOVIES</a>
          <a href="#">TV</a>
          <a href="#">GAMES</a>
          <a href="#">COLLECTIBLES</a>
          <a href="#">VIDEOS</a>
          <a href="#">FANS</a>
          <a href="#">NEWS</a>
          <a href="#">SHOP</a>
        </div>

      </nav>
    </div>
  </header>
    
  
</template>

<script>
export default {
  
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