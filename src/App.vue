<template>
  <NavigationVu />
  <home-vu />
  <ServiceVu />
 
</template>

<script >
import HomeVu from './components/HomeVu.vue';
import NavigationVu from './components/NavigationVu.vue';
import ServiceVu from './components/ServiceVu.vue';

export default{
  components : {
    NavigationVu,
    HomeVu,
    ServiceVu
  }
}

</script>

<style scoped>

</style>
