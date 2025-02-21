<template>
  <AppNavbar />
  <AppSlider/>
  <div class="container">
  <div class="row">
    <div class="col-md-10">
      <AppInventory/>
    </div>
    <div class="col-md-2">

    </div>
  </div>
</div>
</template>

<script>
import AppNavbar from './components/Navber.vue';
import AppSlider from './components/Slider.vue';
import AppInventory from './components/Inventory.vue';

export default {
  name: 'App',
  components: {
    AppNavbar,
    AppSlider,
    AppInventory    
  }
}
</script>
