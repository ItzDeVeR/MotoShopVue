<template>
    <div class="MainDiv">
        <p class="SubscribeText">Подписаться на рассылку</p>
        <p class="MainText">Подпишитесь на нашу рассылку, чтобы первыми узнавать о последних тенденциях, новых
            поступлениях и эксклюзивных предложениях.<br>Вы можете отписаться в любое время.</p>
        <div class="EmailDiv">
            <input placeholder="Введите ваш email">
            <button>Подписаться</button>
        </div>
    </div>
</template>

<style scoped>
.EmailDiv {
    display: flex;
    justify-content: center;
    padding: 50px;
    /* qwe */
}

.EmailDiv input {
    font-size: 20px;
    color: #000;
    border: 1px solid red;
    border-radius: 5px;
    background-color: #fff;
    padding: 10px;
    margin: 0px 40px;
}

.EmailDiv button {
    font-size: 20px;
    border-radius: 5px;
    background-color: red;
    color: #000;
    padding: 0px 20px;
    border: 0px;
    cursor: pointer;
}

.SubscribeText {
    font-size: 32px;
    font-weight: bold;
    margin: 40px auto;
    text-align: center;
}

.MainText {
    text-align: center;
    margin: 0 auto;
    margin-left: auto;
}

.MainDiv {
    display: flex;
    flex-direction: column;
    background: url("../../public/footer-top.jpg") center;
}

.MainDiv p {
    color: #000;
}

* {
    background-color: transparent;
}

@media (max-width: 1024px) {
    .EmailDiv {
        flex-direction: column;
    }
    
    .EmailDiv button {
        margin-top: 10px;
        padding: 10px 0px;
    }

    .EmailDiv input{
        margin: 0px;
    }
}
</style>