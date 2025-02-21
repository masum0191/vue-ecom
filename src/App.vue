<template>
  <AppNavbar />
  <AppSlider/>
</template>

<script>
import AppNavbar from './components/Navber.vue';
import AppSlider from './components/Slider.vue';

export default {
  name: 'App',
  components: {
    AppNavbar,
    AppSlider    
  }
}
</script>
