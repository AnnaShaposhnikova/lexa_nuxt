<template>
    <div class="container">
        <article>
            <div class="row justify-content-center">
                <div class="col-sm-8 py-4 text-center">
                    <h3>Трехместный номер на первом этаже</h3>
                    <p>
                        На первом этаже здания расположен один номер на этаж,
                        имеющий независимый вход с прихожей. В номере сделан
                        ремонт в 2019 году, частично замененена мебель в 2020
                        году. Общая площадь номера – 30 м², площадь комнаты - 22
                        м². Максимальное размещение номере 3+1 (дополнительное
                        место - детская кроватка).
                    </p>
                </div>
            </div>
            <div class="row justify-content-center px-2">
                <figure class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
                    <img
                        v-img:room1
                        src="/images/rooms/1_etag_1.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
                    <img
                        v-img:room1
                        src="/images/rooms/1_etag_2.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
                    <img
                        v-img:room1
                        src="/images/rooms/1_etag_3.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
                    <img
                        v-img:room1
                        src="/images/rooms/1_etag_4.jpg"
                        class="my_img img-fluid"
                    />
                </div>
            </div>

            <div class="row justify-content-center mt-3">
                <div class="col-sm-9">
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/online.png"
                                description="Wi-Fi"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/air-conditioner.png"
                                description="Кондиционер"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/shower.png"
                                description="Душ"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/sofa.png"
                                description="Раскладной диван-кровать"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/double-bed.png"
                                description="Двуспальная кровать"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/mini-bar.png"
                                description="Холодильник"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/tv.png"
                                description="Телевизор"
                            ></RoomIcon>
                        </div>
                    </div>
                </div>
            </div>
        </article>
        <article>
            <span class="card border-bottom-5 border-primary my-4"></span>
            <div class="row justify-content-center">
                <div class="col-sm-8 py-4 text-center">
                    <h3>Трехместный номер на втором этаже</h3>
                    <p>
                        На втором этаже здания расположен один номер на этаж,
                        имеющий независимый вход с прихожей.В номере сделан
                        ремонт в 2019 году, частично замененена мебель в 2020
                        году. Общая площадь номера – 30 м², площадь комнаты - 22
                        м² Максимальное размещение в номере 3 человека.
                    </p>
                </div>
            </div>
            <div class="row justify-content-center px-2">
                <figure class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
                    <img
                        v-img:room2
                        src="/images/rooms/2_etag_1.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
                    <img
                        v-img:room2
                        src="/images/rooms/2_etag_2.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
                    <img
                        v-img:room2
                        src="/images/rooms/2_etag_3.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
                    <img
                        v-img:room2
                        src="/images/rooms/2_etag_4.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
            </div>
            <div class="row justify-content-center mt-3">
                <div class="col-sm-9">
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/online.png"
                                description="Wi-Fi"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/air-conditioner.png"
                                description="Кондиционер"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/shower.png"
                                description="Душ"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/sofa.png"
                                description="Раскладной диван-кровать"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/double-bed.png"
                                description="Двуспальная кровать"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/mini-bar.png"
                                description="Холодильник"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/tv.png"
                                description="Телевизор"
                            ></RoomIcon>
                        </div>
                    </div>
                </div>
            </div>
        </article>
        <span class="card border-bottom-5 border-primary my-4"></span>
        <article>
            <div class="row justify-content-center">
                <div class="col-sm-8 py-4 text-center">
                    <h3>Трехместный номер на третьем этаже</h3>
                    <p>
                        На третьем этаже здания расположен один номер на этаж.
                        Номер имеtт независимый вход. Общая площадь номера – 25
                        м², площадь комнаты - 22 м², площадь балкона - 3 м²
                        Максимальное размещение номере 3 человека. Также есть
                        выход на деревянную террасу с шезлонгами. Во второй
                        половине дня терраса находится в тени, что позволит
                        провести Ваш дневной сон на свежем воздухе.
                    </p>
                </div>
            </div>
            <div class="row justify-content-center px-3">
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room3
                        src="/images/rooms/3_etag_1.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room3
                        src="/images/rooms/3_etag_2.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room3
                        src="/images/rooms/3_etag_3.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room3
                        src="/images/rooms/3_etag_4.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
            </div>

            <div class="row justify-content-center mt-3">
                <div class="col-sm-9">
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/online.png"
                                description="Wi-Fi"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/air-conditioner.png"
                                description="Кондиционер"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/shower.png"
                                description="Душ"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/sofa.png"
                                description="Нераскладной диван"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/double-bed.png"
                                description="Двуспальная кровать"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/single-bed.png"
                                description="Односпальная кровать"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/tv.png"
                                description="Телевизор"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/electric-teapot.png"
                                description="Электрочайник"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/mini-bar.png"
                                description="Холодильник"
                            ></RoomIcon>
                        </div>
                    </div>
                </div>
            </div>
        </article>
        <span class="card border-bottom-5 border-primary my-4"></span>

        <article>
            <div class="row justify-content-center">
                <div class="col-sm-8 py-4 text-center">
                    <h3>Трехместный номер на втором этаже</h3>
                    <p>
                        На втором этаже здания расположен один номер на этаж,
                        имеющий независимый вход с прихожей и балкон. Дом
                        построен в 2019 году, вся мебель новая. Общая площадь
                        номера – 32 м², площадь комнаты - 22 м², площадь балкона
                        - 2 м² Максимальное размещение номере 3 человека
                    </p>
                </div>
            </div>
            <div class="row justify-content-center px-3">
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room4
                        src="/images/rooms/banya_1.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room4
                        src="/images/rooms/banya_2.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room4
                        src="/images/rooms/banya_3.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room4
                        src="/images/rooms/banya_4.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
            </div>

            <div class="row justify-content-center mt-3">
                <div class="col-sm-9">
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/online.png"
                                description="Wi-Fi"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/air-conditioner.png"
                                description="Кондиционер"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/shower.png"
                                description="Душ"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/sofa.png"
                                description="Раскладной диван"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/double-bed.png"
                                description="Двуспальная кровать"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/single-bed.png"
                                description="Односпальная кровать"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/tv.png"
                                description="Телевизор"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/mini-bar.png"
                                description="Холодильник"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/electric-teapot.png"
                                description="Электрочайник"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/tableware.png"
                                description="Набор посуды"
                            ></RoomIcon>
                        </div>
                    </div>
                </div>
            </div>
        </article>
        <span class="card border-bottom-5 border-primary my-4"></span>
        <article>
            <div class="row justify-content-center">
                <div class="col-sm-8 py-4 text-center">
                    <h3>Четырехместный номер на втором этаже</h3>
                    <p>
                        На втором этаже здания расположен один двухкомнатный
                        номер на этаж, имеющий независимый вход. Общая площадь
                        номера – 26 м², площадь комнаты - 13 м², Также есть
                        выход на деревянную террасу с шезлонгами. Во второй
                        половине дня терраса находится в тени, что позволит
                        провести Ваш дневной сон на свежем воздухе. Максимальное
                        размещение номере 4 человека
                    </p>
                </div>
            </div>
            <div class="row justify-content-center px-3">
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room5
                        src="/images/rooms/4mestny_1.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room5
                        src="/images/rooms/4mestny_2.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room5
                        src="/images/rooms/4mestny_3.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
                <figure class="col-lg-3 col-md-6 col-sm-12 p-2 text-center">
                    <img
                        v-img:room5
                        src="/images/rooms/4mestny_4.jpg"
                        class="my_img img-fluid"
                    />
                </figure>
            </div>

            <div class="row justify-content-center mt-3 pb-2">
                <div class="col-sm-9">
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/online.png"
                                description="Wi-Fi"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/air-conditioner.png"
                                description="Кондиционер"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/shower.png"
                                description="Душ"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/sofa.png"
                                description="Раскладной диван"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/double-bed.png"
                                description="Двуспальная кровать"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/single-bed.png"
                                description="Односпальная кровать"
                            ></RoomIcon>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/tv.png"
                                description="Телевизор"
                            ></RoomIcon>
                        </div>
                        <div class="col-lg-6 col-sm-12 mt-3">
                            <RoomIcon
                                src="/images/icons/mini-bar.png"
                                description="Холодильник"
                            ></RoomIcon>
                        </div>
                    </div>
                </div>
            </div>
        </article>
    </div>
</template>

<script>
export default {
    layout: "default"
};
</script>
