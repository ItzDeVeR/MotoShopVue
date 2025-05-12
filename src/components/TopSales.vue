<template>
    <div class="MainDiv">
        <p class="MainTitle">Наша мото-продукция</p>
        <div class="allCards">
            <div class="curCard">
                <img alt="helmet" src="../../public/exohelmet.jpg" />
                <p class="title">EOX MOTOHELMET</p>
                <p class="subtitle">394 отзыва</p>
                <p class="content">
                    EOX – наши мотошлемы EOX с полной защитой лица совместимы с
                    Bluetooth и имеют сертификат DOT.
                    Оснащённые технологией поглощения ударов RHEON и совместимые с аудиосистемой Cardo Shockwave
                    Bluetooth, они позволяют вам оставаться на связи с группой до 15 райдеров.
                    Углеродное волокно делает шлем EOX невероятно лёгким, а поле зрения в 215° обеспечивает отличную
                    обзорность.
                    В сочетании с дизайном Ruroc, шлемы EOX предлагают максимальную безопасность,
                    производительность и комфорт.
                </p>
                <button class="orderButton">Заказать</button>
            </div>
            <div class="curCard">
                <img alt="helmet" src="../../public/at4helmet.jpg" />
                <p class="title">AT4.0 CARBON</p>
                <p class="subtitle">2767 отзыв</p>
                <p class="content">
                    AT4.0 CARBON — четвертое поколение полноразмерного мотошлема AT. Эта культовая модель из карбона
                    отличается сверхпрочным и легким корпусом, панорамным обзором и технологией RHEON, встроенной в
                    многослойный внутренний амортизатор. Соответствуя стандартам DOT FMVSS 218 и ECE 22.06, а также
                    поддерживая полную совместимость с Bluetooth-системой Shockwave, а в сочетании с уникальным дизайном
                    Ruroc AT4.0 CARBON — это идеальный шлем
                    для города.
                </p>
                <button class="orderButton">Заказать</button>
            </div>
            <div class="curCard">
                <img alt="helmet" src="../../public/at4trackhelmet.jpg" />
                <p class="title">AT4.0 STREET</p>
                <p class="subtitle">394 отзыва</p>
                <p class="content">
                    AT4.0 STREET — это легкий цельнокомпозитный мотошлем. Созданный без компромиссов, STREET — наш самый
                    доступный шлем на сегодня. Соответствуя стандартам ECE 22.06 и DOT, а также обладая полной
                    совместимостью с Bluetooth-системой Shockwave, STREET сочетает в себе безопасность и стиль.
                    (Название модели "AT4.0 STREET" сохранено без изменений, как и ключевые термины "Shockwave",
                    поскольку они являются стандартами или фирменными наименованиями.)
                </p>
                <button class="orderButton">Заказать</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
.MainTitle {
    font-size: 32px;
    font-weight: bold;
    padding-bottom: 40px;
    margin: 0 auto;
}

.orderButton {
    all: unset;
    cursor: pointer;
    background-color: #fff;
    color: #000;
    border-radius: 10px;
    padding: 10px 20px;
    margin-bottom: 50px;
}

.orderButton:hover {
    color: #fff;
    background-color: #BDBDBD;
}

.title {
    font-size: 20px;
    padding: 10px 0px;
    font-weight: bold;
    text-align: center;
}

.subtitle {
    font-size: 12px;
    color: #BDBDBD;
}

.content {
    font-size: 14px;
    padding: 15px 0px;
    text-align: justify;
}

.allCards {
    display: flex;
    overflow: hidden;
    justify-content: space-evenly;
}

.curCard {
    display: flex;
    flex-direction: column;
    width: 22rem;
    align-items: center;
}

.curCard img {
    width: 14rem;
    border-radius: 150px;
}

.MainDiv {
    display: flex;
    flex-direction: column;
}

@media (max-width: 1024px) {
    .allCards {
        flex-direction: column;
        align-items: center;
    }

    .MainTitle {
        text-align: center;
        font-size: 24px;
    }
}
</style>