<script setup lang="ts">
</script>

<template>
    <div class="main-container">
        <h6>Raikko Prants</h6>
        <h2>Software Developer</h2>
        <p>I'm a <span class="highlight">Junior Software Developer,</span> looking for an internship or my first job. I am from <span class="highlight">Estonia based in Tartu,</span> but
            capable
            of work that are based near Ida-Virumaa. I have a small background in designing websites but have mostly done
            devlopment.
            My preferred languages are <span class="highlight">Java, JavaScript, Python,</span> but I have experience in many more. I am passionate and
            enjoy the work I do.
            <span class="highlight">I'm a teamplayer and a hardworker.</span>
        </p>
        <div class="image-container">
            <img class="image" src="../assets/me.jpg" />
        </div>
    </div>
</template>
<style scoped>
.main-container {
    display: flex;
    justify-content: center;
    flex-direction: column;
    height: 100vh;
    width: 50vw;
    margin-left: auto;
    margin-right: auto;
}

.main-container h6 {
    color: rgba(255, 248, 238, .51);
    letter-spacing: 5px;
    margin-top: 20px;
    margin-bottom: 20px;
    font-size: 40px;
    font-weight: 400;
    text-transform: uppercase;
    line-height: 18px;
    box-sizing: border-box;
}

.main-container h2 {
    margin: .67em 0;
    color: #fff8ee;
    background-image: linear-gradient(56deg, #9660f9, #40f384);
    margin-left: -2px;
    padding-bottom: 3px;
    font-size: 70px;
    font-weight: 400;
    line-height: 65px;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

.main-container p {
    max-width: 880px;
    margin-top: 30px;
    padding-right: 20px;
    font-size: 32px;
    line-height: 35px;
    color: #fcf7f0;
}

.highlight {
    background-color: #6688ed;
    border-radius: 15px;
}

.image-container {
    display: flex;
    justify-content: center;
    align-items: center;
}

.image {
    margin-top: 20px;
    border-radius: 20%;
    width: 320px;
    height: 400px;
}
</style>