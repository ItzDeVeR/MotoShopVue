<template>
    <div class="MainDiv">
        <video autoplay muted loop playsinline class="MainVideo" src="../../public/videoBG.mp4" />
        <div class="content">
            <img src="../../public/mtHelmetsLogo.png" />
        </div>
    </div>
</template>

<style scoped>
.MainDiv {
    position: relative;
    border-top: 5px solid #000;
}

.MainVideo {
    object-fit: cover;
    width: 100%;
    height: auto;
    position: relative;
    z-index: 0;
}

.content {
    position: absolute;
    top: 0;
    z-index: 1;
}

.content img {
    width: 20vw;
    margin: 20px;
}

*{
    background-color: transparent;
}
</style>