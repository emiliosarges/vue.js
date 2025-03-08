<script lang="ts">
import Banner from './components/Banner.vue';
import ConteudoPrincipal from './components/ConteudoPrincipal.vue';

//Quando propriedade e valor são igual, podemos deixar somente o nome da propriedade em vez de: { Banner: Banner }
export default {
  components: { Banner, ConteudoPrincipal } 
}

</script>

<template>
  <Banner />
  <ConteudoPrincipal />
</template>

<style scoped>

</style>