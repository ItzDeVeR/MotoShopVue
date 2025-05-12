<template>
    <div class="MainDiv">
        <p class="mainText">Наши бренды</p>
        <div class="allLogos">
            <a href="https://www.airoh.com/"><img src="../../public/airohLogo.png" /></a>
             <a href="https://www.axxis-helmets.com/"><img src="../../public/axxisLogo.png" /></a>
             <a href="https://www.ruroc.com/"><img src="../../public/rurocLogo.png" /></a>
             <a href="https://en.stylmartin.it/"><img src="../../public/stylMartinLogo.jpg" /></a>
        </div>
    </div>
</template>

<style scoped>
.allLogos img{
    width: 150px;
    border-radius: 30px 10px;
}

.allLogos {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
}

.mainText {
    font-size: 32px;
    font-weight: bold;
    padding-bottom: 50px;
    background-color: transparent;
    margin: 40px auto 0;
}

.MainDiv {
    display: flex;
    flex-direction: column;
    background: url('../../public/pitbiker.jpg');
    /* height: 100vh; */
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    padding-bottom: 90px;
}

*{
    background-color: transparent;
}

@media (max-width: 1024px) {
    .allLogos img{
        margin: 10px;
    }
}
</style>