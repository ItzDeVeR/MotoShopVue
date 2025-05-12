<template>
    <div class="mainDiv">
        <div class="mainText">
            Экипировка, которая спасает жизни – без компромиссов!
        </div>
        <img style="margin: 15px;" src="../../public/scrolldown.png" class="scrollImg" height="50" />
    </div>
</template>

<style scoped>
.mainText {
    font-family: "Comfortaa", sans-serif;
    font-size: 32px;
    color: #fff;
    font-weight: bold;
    text-align: center;
}

.mainDiv {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    flex-direction: column;
    padding-bottom: 70px;
    background:
        linear-gradient(rgba(0, 0, 0, 0.1),
            rgba(0, 0, 0, 1)), url('../../public/background.jpg');
    /* height: 100%; */
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;

    /* width: 100vw; */
    height: 100vh;
}

* {
    background-color: transparent;
}
</style>