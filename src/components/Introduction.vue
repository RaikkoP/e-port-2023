<script setup lang="ts">
</script>

<template>
    <div class="main-container">
        <hr>
        <h2>
            <span class="title-hover">I'm</span>
        </h2>
        <span class="title-hover">
            <h1>
                Raikko
            </h1>
        </span>
        <span class="title-hover">
            <h1>
                Prants
            </h1>
        </span>
        <hr>
    </div>
</template>
    
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Bungee&display=swap');

.main-container {
    color: white;
    display: flex;
    cursor: default;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    width: 100vw;
    margin-bottom: 25em;
    animation: jumpIn 0.5s;
}

.main-container h1 {
    font-size: 200px;
    transform: rotate(-30deg);
}

.main-container h2 {
    font-size: 100px;
    transform: rotate(-30deg);
}

.main-container hr {
    width: 500px;
    height: 10px;
    background-color: white;
    transform: rotate(-30deg);
}

.title-hover:hover {
    animation: letterSpace 0.5s ease-in-out forwards;
    color: orangered;
}

@keyframes jumpIn {
    0% {
        scale: 0;
    }

    100% {
        scale: 1;
    }
}
@keyframes letterSpace {
    0% {
        letter-spacing: 0px;
        scale:1;
    }
    100% {
        letter-spacing: 10px;
        scale: 1.1;
    }
}
</style>