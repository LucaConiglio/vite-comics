<template>
  <section>
    <div class="container">
      <h3 class="text-white py-4">-->Content goes here&lt--  </h3>
    </div>
  </section>
  <TheContacts></TheContacts>
</template>
<script>
import TheContacts from './TheContacts.vue';
export default {
  components : {TheContacts},
}
</script>
<style scoped>
section{
  background-color: black;
  padding: 2rem 0;
}
</style>