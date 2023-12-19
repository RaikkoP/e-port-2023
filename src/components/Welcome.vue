<script setup lang="ts">

</script>

<template>
    <div class="main-container">
        <span id="title-hover"><hr></span>
        <h1>
            <span id="title-hover">R</span>
            <span id="title-hover">a</span>
            <span id="title-hover">i</span>
            <span id="title-hover">k</span>
            <span id="title-hover">k</span>
            <span id="title-hover">o</span>
        </h1>
        <h1>
            <span id="title-hover">P</span>
            <span id="title-hover">r</span>
            <span id="title-hover">a</span>
            <span id="title-hover">n</span>
            <span id="title-hover">t</span>
            <span id="title-hover">s</span>
        </h1>
        <span id="title-hover"><hr></span>
    </div>
</template>
    
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Bungee&display=swap');
.main-container {
    font-family: 'Bungee', sans-serif;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    width: 100vw;
}
.main-container h1 {
    font-size: 200px;
    letter-spacing: 20px;
    transform: rotate(-30deg);
}
.main-container hr {
    width: 500px;
    height: 10px;
    background-color: white;
    transform: rotate(-30deg);
}
#title-hover:hover {
    letter-spacing: 70px;
    color: orangered;
}
</style>