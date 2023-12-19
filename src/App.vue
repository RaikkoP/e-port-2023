<script setup lang="ts">
import Welcome from './components/Welcome.vue'
import {ref, onMounted, onUnmounted} from 'vue'
let posX = ref('');
let posY = ref('');
  

const trackMousePosition = (e: MouseEvent) => {
  posX.value = e.clientX -50 + 'px';
  posY.value = e.clientY -50 + 'px';
  console.log(posX.value, posY.value)
}
onMounted(() => {
  window.addEventListener('mousemove', trackMousePosition);
})
onUnmounted(() => {
  window.removeEventListener('mousemove', trackMousePosition);
})

</script>


<template>
  <div class="mouseCircle" :style="{'background': `radial-gradient(circle at ${posX} ${posY}, transparent 10%, rgba(0,0,0,0.8) 80%)`}"/>
  <Welcome />
  
</template>

<style scoped>
.mouseCircle {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
}
</style>
