<script>
import TheHeader from './components/TheHeader.vue';
import TheMain from './components/TheMain.vue';
import TheFooter from './components/TheFooter.vue';
import TheDownFooter from './components/TheDownFooter.vue';

export default {
  components : {TheHeader, TheMain , TheFooter, TheDownFooter,},
  data () {
    return {



    }
  },
  methods : {


},
mounted () {

  
},
computed : {

},


}
</script>

<template>
  <TheHeader></TheHeader>
  <TheMain></TheMain>
  <TheFooter></TheFooter>
  <TheDownFooter></TheDownFooter>
</template>

<style lang="scss">
@use "./styles/general.scss";

</style>
