<template>
  <AppNavbar />
  <AppSlider/>
  <div class="container p-3">
  <div class="row">
    <div class="col-md-10">
      <AppInventory/>
    </div>
    <div class="col-md-2">
      <AppCart/>
    </div>
  </div>
  
</div>
<footer>
    <p class="text-center bg-dark">Vue-Ecom &copy; 2025</p>
  </footer>
</template>

<script>
import AppNavbar from './components/Navber.vue';
import AppSlider from './components/Slider.vue';
import AppInventory from './components/Inventory.vue';
import AppCart from './components/Cart.vue';

export default {
  name: 'App',
  components: {
    AppNavbar,
    AppSlider,
    AppInventory,
    AppCart   
  }
}
</script>
