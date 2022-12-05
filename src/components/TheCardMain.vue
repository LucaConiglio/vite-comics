<template>
  <section class="other-section">
    <div class="container">
      <div class="text-white bg-primary fw-bold fs-4 py-2 px-4 current-series">CURRENT SERIES</div>
      <div class="row g-4">
        <div v-for="(image, i) in comicsLinks" key="i" class="col-2">
          <div class="mb-4">
            <div class="my-imgs">
              <img :src="image.thumb" :alt="image.type">
            </div>
          </div>
          <div>
            <h6 class="text-white">{{image.series}}</h6>
          </div>
        </div>
      </div>
      <div class="text-center mt-4">
        <button class=" my-btn"> LOAD MORE</button>
      </div>
      
    </div>
  </section>
</template>

<script>
import dcComics from "../dc-comics.js";
export default {
  
  data() {
    return {
      comicsLinks : dcComics,
    }
  },
  
    
}
</script>
<style scoped lang="scss">
.other-section{
   background-color: #1c1c1c;
   padding: 2rem 0;
   .current-series{
    display: inline;
    position: relative;
    bottom: 48px;
    
   }
   
   .my-imgs{
    
    img{
      width: 100%;
      height:200px;
      object-fit: cover;
      object-position: top;
      opacity: 0.5;

      &:hover{
        opacity: 1;
      }
    }
   }
   .my-btn{
    background-color: #0282f9;
    color: white;
    padding: 0.5rem 4rem;
    font-weight: 600;
   }
 }
</style>