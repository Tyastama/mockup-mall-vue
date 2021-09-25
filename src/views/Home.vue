<template>
  <div class="home">
    <Navbar />
    <Slider />
    <Hilite />
    <Produk />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue';
import Slider from '@/components/Slider.vue';
import Hilite from '@/components/Hilite.vue';
import Produk from '@/components/Produk.vue';

export default {
  name: 'Home',
  components: {
    Navbar,
    Slider,
    Hilite,
    Produk,
  },
};
</script>
