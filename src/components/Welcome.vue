<script setup lang="ts">
</script>

<template>
    <div class="main-container">
      <h1><scope class="title">Hey</scope> 😎</h1>
       <h3>Would Be Nice If You Scrolled 🔽</h3>
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
    animation: fadeIn 2s;
}
.main-container h3 {
    animation: fadeIn 2s;
}
.title {
    background: -webkit-linear-gradient(#ff9b05, #e5dd09);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

@keyframes fadeIn {
    0% {opacity: 0;}
    100% {opacity: 1;}
}


</style>