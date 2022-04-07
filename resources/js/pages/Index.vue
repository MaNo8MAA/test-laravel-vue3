<template>
  <div>
    <hero />
    <show-all-products />
  </div>
</template>

<script>
import { defineComponent } from 'vue';

import Hero from '../components/Home/Hero.vue';

import ShowAllProducts from '../components/Products/ShowAllProducts.vue';

export default defineComponent({
  components: { Hero, ShowAllProducts },
});
</script>
