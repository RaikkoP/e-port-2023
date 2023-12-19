<script setup lang="ts">
import Welcome from './components/Welcome.vue'
import { ref, onMounted, onUnmounted } from 'vue';
let posX = ref(0);
let posY = ref(0);

const trackMouse = (e: MouseEvent) => {
    posX.value = e.clientX - 10;
    posY.value = e.clientY - 10;
    console.log(posX.value, posY.value)
}
onMounted(() => {
    window.addEventListener("mousemove", trackMouse);
})
onUnmounted(() => {
    window.removeEventListener("mousemove", trackMouse);
})

</script>


<template>
    <div class="cursor" :style="{ left: posX + 'px', top: posY + 'px' }"></div>
    <Welcome />
</template>

<style scoped>
.cursor {
    position: absolute;
    width: 15px;
    height: 15px;
    background-color: white;
    border: 1px solid black;
    border-radius: 100%;
    box-shadow: 0 0 10px 5px white;
}

</style>
