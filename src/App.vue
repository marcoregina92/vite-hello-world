<script>
import HelloWorld from './components/HelloWorld.vue'
import firstComponent from './components/firstComponent.vue'

export default {
  components: {
    HelloWorld,
    firstComponent
  }
}
</script>



<template>
  <div>
    Benvenuto nella tua app in Vue.js
  </div>
  <HelloWorld />
  <firstComponent />
</template>

<style scoped></style>
