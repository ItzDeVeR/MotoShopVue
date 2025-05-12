<template>
    <div class="MainDiv">
        <div class="Links">
            <a href="/">Политика конфиденциальности</a>
            <a href="/">Условия и положения</a>
            <a href="/">Вакансии</a>
        </div>
        <img src="../../public/logos2.png" />
        <p>Интернет-магазин<br>© 2025 Все права защищены.</p>
    </div>
</template>

<style scoped>
.MainDiv {
    display: flex;
    background-color: #1A1A1A;
    justify-content: space-around;
    align-items: center;
    padding: 50px;
}

.MainDiv img {
    width: 40vh;
    height: auto;
    margin: 20px 0;
}

.Links {
    display: flex;
    flex-direction: column;
    align-items: center;
}

* {
    background-color: transparent;
}

@media (max-width: 1024px) {
    .MainDiv {
        flex-direction: column;
    }
}
</style>