<script lang="ts">
import Banner from './components/Banner.vue';
import ConteudoPrincipalVue from './components/ConteudoPrincipal.vue';

export default {
  components: { Banner: Banner, ConteudoPrincipalVue: ConteudoPrincipalVue }
}
</script>

<template>
  <Banner />
  <ConteudoPrincipalVue/>
</template>
