<template>
  <section class="my-section">
    <div class="container">
    </div>
  </section>
  <TheCardMain></TheCardMain>
  <TheContacts></TheContacts>
</template>

<script>
import TheCardMain from './TheCardMain.vue';
import TheContacts from './TheContacts.vue';
export default {
  components : { TheContacts, TheCardMain, TheCardMain },

}
</script>
<style scoped lang="scss">

.my-section{
  background-image: url("./jumbotron.jpg");
  height: 400px;
  background-position: top;
  background-size: cover;
}
</style>