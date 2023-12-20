<script setup lang="ts">
import Welcome from './components/Welcome.vue'
import Introduction from './components/Introduction.vue'
import AboutMe from './components/Aboutme.vue'
</script>


<template>
    <div class="background">
        <Welcome />
        <Introduction />
        <AboutMe />
        <div>
            <h1>Test</h1>
        </div>
    </div>
</template>

<style scoped>
.background {
    background-image:
    linear-gradient(to bottom, rgba(245, 246, 252, 0.52), rgba(174, 27, 137, 0.73), rgba(117, 19, 93, 0.73));  
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
}
</style>
