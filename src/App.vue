<script>
import TheHeader from './components/TheHeader.vue';
import TheMain from './components/TheMain.vue';
import TheFooter from './components/TheFooter.vue';
import SignUpFooter from './components/SignUpFooter.vue';

export default {
  components : {TheHeader, TheMain , TheFooter, SignUpFooter},
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
  <SignUpFooter></SignUpFooter>
</template>

<style lang="scss">
@use "./styles/general.scss";

</style>
