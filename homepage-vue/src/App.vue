<template>
  <div id="app" class="flex flex-col min-h-screen overflow-y-auto overflow-x-hidden mb-10">
    <Nav/>
    <Homepage class="flex-grow"/>
    <div class="grid grid-cols-12 mt-40">
      <div class="col-span-2"/>
      <span class="text-gray-300 col-span-10"></span>
    </div>
  </div>
</template>

<script>
import Homepage from './components/Homepage.vue'
import Nav from './components/Nav.vue'

export default {
  name: 'App',
  components: {
    Homepage,
    Nav
  }
}
</script>
