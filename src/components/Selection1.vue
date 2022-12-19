<template>
    <div class="container mt-3">
        <div class="row">
            <div class="col-md-4 p-4" style="text-align: left;">
                <img src="../assets/images/ikon1.webp" alt="">
                <h2 class="mt-2">Cek promo sebelum bepergian, kuy!</h2>
                <button class="btn btn-outline-primary mt-3">Lihat semua promo</button>
            </div>
            <div class="col-md-8 p-4">
                <div class="">
                    <div role="tabpanel ">
                        <!-- List group -->
                        <div class="list-group list-group-horizontal position-relative overflow-auto w-100" id="myList"
                            role="tablist">
                            <a class="list-group-item list-group-item-action me-3 rounded-pill text-nowrap active"
                                data-bs-toggle="list" href="#semua" role="tab">Semua</a>
                            <a class="list-group-item list-group-item-action me-3 rounded-pill text-nowrap"
                                data-bs-toggle="list" href="#hotel" role="tab">Hotel</a>
                            <a class="list-group-item list-group-item-action me-3 rounded-pill text-nowrap"
                                data-bs-toggle="list" href="#vila" role="tab">Vila & Apt</a>
                            <a class="list-group-item list-group-item-action me-3 rounded-pill text-nowrap"
                                data-bs-toggle="list" href="#toDo" role="tab">To do</a>
                            <a class="list-group-item list-group-item-action me-3 rounded-pill text-nowrap"
                                data-bs-toggle="list" href="#kereta" role="tab">Kereta Api</a>
                            <a class="list-group-item list-group-item-action me-3 rounded-pill text-nowrap"
                                data-bs-toggle="list" href="#mobil" role="tab">Sewa Mobil</a>
                            <a class="list-group-item list-group-item-action me-3 rounded-pill text-nowrap"
                                data-bs-toggle="list" href="#bandara" role="tab">Jemputan Bandara</a>
                        </div>

                        <!-- Tab panes -->
                        <div class="tab-content mt-3">
                            <div class="tab-pane active" id="semua" role="tabpanel">
                                <div class="row">
                                    <div class="col-12">
                                        <div id="carouselExampleIndicators2" class="carousel slide"
                                            data-ride="carousel">

                                            <div class="carousel-inner">
                                                <div class="carousel-item active overflow-y: auto">
                                                    <div class="row">

                                                        <div class="col-md-4 mb-3">
                                                            <div class="card">
                                                                <img class="img-fluid" alt="100%x280"
                                                                    src="../assets/images/diskon1.webp">
                                                            </div>
                                                        </div>
                                                        <div class="col-md-4 mb-3">
                                                            <div class="card">
                                                                <img class="img-fluid" alt="100%x280"
                                                                    src="../assets/images/diskon1.webp">
                                                            </div>
                                                        </div>
                                                        <div class="col-md-4 mb-3">
                                                            <div class="card">
                                                                <img class="img-fluid" alt="100%x280"
                                                                    src="../assets/images/diskon1.webp">
                                                            </div>
                                                        </div>

                                                    </div>
                                                </div>
                                                <div class="carousel-item">
                                                    <div class="row">

                                                        <div class="col-md-4 mb-3">
                                                            <div class="card">
                                                                <img class="img-fluid" alt="100%x280"
                                                                    src="https://images.unsplash.com/photo-1532771098148-525cefe10c23?ixlib=rb-0.3.5&amp;q=80&amp;fm=jpg&amp;crop=entropy&amp;cs=tinysrgb&amp;w=1080&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjMyMDc0fQ&amp;s=3f317c1f7a16116dec454fbc267dd8e4">
                                                                <div class="card-body">
                                                                    <h4 class="card-title">Special title treatment
                                                                    </h4>
                                                                    <p class="card-text">With supporting text below
                                                                        as a natural lead-in to additional content.
                                                                    </p>

                                                                </div>

                                                            </div>
                                                        </div>
                                                        <div class="col-md-4 mb-3">
                                                            <div class="card">
                                                                <img class="img-fluid" alt="100%x280"
                                                                    src="https://images.unsplash.com/photo-1532715088550-62f09305f765?ixlib=rb-0.3.5&amp;q=80&amp;fm=jpg&amp;crop=entropy&amp;cs=tinysrgb&amp;w=1080&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjMyMDc0fQ&amp;s=ebadb044b374504ef8e81bdec4d0e840">
                                                                <div class="card-body">
                                                                    <h4 class="card-title">Special title treatment
                                                                    </h4>
                                                                    <p class="card-text">With supporting text below
                                                                        as a natural lead-in to additional content.
                                                                    </p>

                                                                </div>
                                                            </div>
                                                        </div>
                                                        <div class="col-md-4 mb-3">
                                                            <div class="card">
                                                                <img class="img-fluid" alt="100%x280"
                                                                    src="https://images.unsplash.com/photo-1506197603052-3cc9c3a201bd?ixlib=rb-0.3.5&amp;q=80&amp;fm=jpg&amp;crop=entropy&amp;cs=tinysrgb&amp;w=1080&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjMyMDc0fQ&amp;s=0754ab085804ae8a3b562548e6b4aa2e">
                                                                <div class="card-body">
                                                                    <h4 class="card-title">Special title treatment
                                                                    </h4>
                                                                    <p class="card-text">With supporting text below
                                                                        as a natural lead-in to additional content.
                                                                    </p>

                                                                </div>
                                                            </div>
                                                        </div>

                                                    </div>
                                                </div>
                                                <div class="carousel-item">
                                                    <div class="row">

                                                        <div class="col-md-4 mb-3">
                                                            <div class="card">
                                                                <img class="img-fluid" alt="100%x280"
                                                                    src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?ixlib=rb-0.3.5&amp;q=80&amp;fm=jpg&amp;crop=entropy&amp;cs=tinysrgb&amp;w=1080&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjMyMDc0fQ&amp;s=ee8417f0ea2a50d53a12665820b54e23">
                                                                <div class="card-body">
                                                                    <h4 class="card-title">Special title treatment
                                                                    </h4>
                                                                    <p class="card-text">With supporting text below
                                                                        as a natural lead-in to additional content.
                                                                    </p>

                                                                </div>

                                                            </div>
                                                        </div>
                                                        <div class="col-md-4 mb-3">
                                                            <div class="card">
                                                                <img class="img-fluid" alt="100%x280"
                                                                    src="https://images.unsplash.com/photo-1532777946373-b6783242f211?ixlib=rb-0.3.5&amp;q=80&amp;fm=jpg&amp;crop=entropy&amp;cs=tinysrgb&amp;w=1080&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjMyMDc0fQ&amp;s=8ac55cf3a68785643998730839663129">
                                                                <div class="card-body">
                                                                    <h4 class="card-title">Special title treatment
                                                                    </h4>
                                                                    <p class="card-text">With supporting text below
                                                                        as a natural lead-in to additional content.
                                                                    </p>

                                                                </div>
                                                            </div>
                                                        </div>
                                                        <div class="col-md-4 mb-3">
                                                            <div class="card">
                                                                <img class="img-fluid" alt="100%x280"
                                                                    src="https://images.unsplash.com/photo-1532763303805-529d595877c5?ixlib=rb-0.3.5&amp;q=80&amp;fm=jpg&amp;crop=entropy&amp;cs=tinysrgb&amp;w=1080&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjMyMDc0fQ&amp;s=5ee4fd5d19b40f93eadb21871757eda6">
                                                                <div class="card-body">
                                                                    <h4 class="card-title">Special title treatment
                                                                    </h4>
                                                                    <p class="card-text">With supporting text below
                                                                        as a natural lead-in to additional content.
                                                                    </p>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane" id="hotel" role="tabpanel">
                                <div class="row flex-row flex-nowrap">

                                    <div class="upcomingfestivals col-6 col-sm-3">

                                        <div class="card card-block">post</div>

                                    </div>

                                    <div class="upcomingfestivals col-6 col-sm-3">

                                        <div class="card card-block">post</div>

                                    </div>

                                    <div class="upcomingfestivals col-6 col-sm-3">

                                        <div class="card card-block">post</div>

                                    </div>

                                    <div class="upcomingfestivals col-6 col-sm-3">

                                        <div class="card card-block">post</div>

                                    </div>

                                    <div class="upcomingfestivals col-6 col-sm-3">

                                        <div class="card card-block">post</div>

                                    </div>

                                    <div class="upcomingfestivals col-6 col-sm-3">

                                        <div class="card card-block">post</div>

                                    </div>

                                    <div class="upcomingfestivals col-6 col-sm-3">

                                        <div class="card card-block">post</div>

                                    </div>

                                    <div class="upcomingfestivals col-6 col-sm-3">

                                        <div class="card card-block">post</div>

                                    </div>

                                </div>
                            </div>
                            <div class="tab-pane" id="vila" role="tabpanel">
                                <div class="multi-carousel" data-bs-interval="3000" data-bs-items="5">
                                    <div class="d-flex justify-content-center m-2 mb-3">
                                        <button class="carousel-control-prev btn btn-pink btn-floating mx-3"
                                            type="button" tabindex="0" data-bs-slide="prev">
                                            <i class="fas fa-angle-left fa-lg"></i>
                                        </button>
                                        <button class="carousel-control-next btn btn-pink btn-floating mx-3"
                                            type="button" tabindex="0" data-bs-slide="next">
                                            <i class="fas fa-angle-right fa-lg"></i>
                                        </button>
                                    </div>
                                    <div class="multi-carousel-inner">
                                        <div class="multi-carousel-item" v-for="x in 3" :key="x">
                                            <div class="card m-2">
                                                <img class="card-img-top w-50"
                                                    src="https://mdbootstrap.com/img/Photos/Square/img(4).jpg"
                                                    alt="Card image cap" />
                                                <div class="card-body">
                                                    <h5 class="card-title">Moda</h5>
                                                    <p class="card-text">Plan B</p>
                                                    <ul class="list-unstyled list-inline my-2">
                                                        <li class="list-inline-item mx-0"><i class="fas fa-star"></i>
                                                        </li>
                                                        <li class="list-inline-item mx-0"><i class="fas fa-star"></i>
                                                        </li>
                                                        <li class="list-inline-item mx-0"><i class="fas fa-star"></i>
                                                        </li>
                                                        <li class="list-inline-item mx-0"><i class="fas fa-star"></i>
                                                        </li>
                                                        <li class="list-inline-item mx-0"><i
                                                                class="fas fa-star-half-alt"></i></li>
                                                    </ul>
                                                    <p class="price mb-0">9,99 $</p>
                                                </div>
                                            </div>
                                        </div>
                                        <!-- <div class="multi-carousel-item">
                                                <div class="card m-2">
                                                    <img class="card-img-top"
                                                        src="https://mdbootstrap.com/img/Photos/Square/img(1).jpg"
                                                        alt="Card image cap" />
                                                    <div class="card-body">
                                                        <h5 class="card-title">Indie City</h5>
                                                        <p class="card-text">Pixies</p>
                                                        <ul class="list-unstyled list-inline my-2">
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="far fa-star"></i></li>
                                                        </ul>
                                                        <p class="price mb-0">14,99 $</p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="multi-carousel-item">
                                                <div class="card m-2">
                                                    <img class="card-img-top"
                                                        src="https://mdbootstrap.com/img/Photos/Square/img(7).jpg"
                                                        alt="Card image cap" />
                                                    <div class="card-body">
                                                        <h5 class="card-title">Year</h5>
                                                        <p class="card-text">Indielectru</p>
                                                        <ul class="list-unstyled list-inline my-2">
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                        </ul>
                                                        <p class="price mb-0">12,99 $</p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="multi-carousel-item">
                                                <div class="card m-2">
                                                    <img class="card-img-top"
                                                        src="https://mdbootstrap.com/img/Photos/Square/img(8).jpg"
                                                        alt="Card image cap" />
                                                    <div class="card-body">
                                                        <h5 class="card-title">L'Hiver Indien</h5>
                                                        <p class="card-text">Baloji</p>
                                                        <ul class="list-unstyled list-inline my-2">
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star-half-alt"></i></li>
                                                        </ul>
                                                        <p class="price mb-0">10,99 $</p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="multi-carousel-item">
                                                <div class="card m-2">
                                                    <img class="card-img-top"
                                                        src="https://mdbootstrap.com/img/Photos/Square/img(6).jpg"
                                                        alt="Card image cap" />
                                                    <div class="card-body">
                                                        <h5 class="card-title">Indie Funk</h5>
                                                        <p class="card-text">Generation Funk</p>
                                                        <ul class="list-unstyled list-inline my-2">
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                        </ul>
                                                        <p class="price mb-0">19,99 $</p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="multi-carousel-item">
                                                <div class="card m-2">
                                                    <img class="card-img-top"
                                                        src="https://mdbootstrap.com/img/Photos/Square/img(2).jpg"
                                                        alt="Card image cap" />
                                                    <div class="card-body">
                                                        <h5 class="card-title">Rockferry</h5>
                                                        <p class="card-text">Duffy</p>
                                                        <ul class="list-unstyled list-inline my-2">
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star-half-alt"></i></li>
                                                        </ul>
                                                        <p class="price mb-0">17,99 $</p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="multi-carousel-item">
                                                <div class="card m-2">
                                                    <img class="card-img-top"
                                                        src="https://mdbootstrap.com/img/Photos/Square/img(3).jpg"
                                                        alt="Card image cap" />
                                                    <div class="card-body">
                                                        <h5 class="card-title">Indie Pop</h5>
                                                        <p class="card-text">Various artists</p>
                                                        <ul class="list-unstyled list-inline my-2">
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="far fa-star"></i></li>
                                                        </ul>
                                                        <p class="price mb-0">9,99 $</p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="multi-carousel-item">
                                                <div class="card m-2">
                                                    <img class="card-img-top"
                                                        src="https://mdbootstrap.com/img/Photos/Square/img(5).jpg"
                                                        alt="Card image cap" />
                                                    <div class="card-body">
                                                        <h5 class="card-title">Rock 'N' Roll</h5>
                                                        <p class="card-text">Chuck Berry</p>
                                                        <ul class="list-unstyled list-inline my-2">
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star-half-alt"></i></li>
                                                        </ul>
                                                        <p class="price mb-0">29,99 $</p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="multi-carousel-item">
                                                <div class="card m-2">
                                                    <img class="card-img-top"
                                                        src="https://mdbootstrap.com/img/Photos/Square/img(9).jpg"
                                                        alt="Card image cap" />
                                                    <div class="card-body">
                                                        <h5 class="card-title">High Voltage</h5>
                                                        <p class="card-text">AC/DC</p>
                                                        <ul class="list-unstyled list-inline my-2">
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                            <li class="list-inline-item mx-0"><i
                                                                    class="fas fa-star"></i></li>
                                                        </ul>
                                                        <p class="price mb-0">24,99 $</p>
                                                    </div>
                                                </div>
                                            </div> -->
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane" id="toDo" role="tabpanel">
                                <div class="bbb_viewed">
                                    <div class="container">
                                        <div class="row">
                                            <div class="col">
                                                <div class="bbb_main_container">
                                                    <div class="bbb_viewed_title_container">
                                                        <h3 class="bbb_viewed_title">Best selling products</h3>
                                                        <div class="bbb_viewed_nav_container">
                                                            <div class="bbb_viewed_nav bbb_viewed_prev"><i
                                                                    class="fas fa-chevron-left"></i></div>
                                                            <div class="bbb_viewed_nav bbb_viewed_next"><i
                                                                    class="fas fa-chevron-right"></i></div>
                                                        </div>
                                                    </div>
                                                    <div class="bbb_viewed_slider_container">
                                                        <div class="owl-carousel owl-theme bbb_viewed_slider">
                                                            <div class="owl-item">
                                                                <div
                                                                    class="bbb_viewed_item discount d-flex flex-column align-items-center justify-content-center text-center">
                                                                    <div class="bbb_viewed_image"><img
                                                                            src="https://res.cloudinary.com/dxfq3iotg/image/upload/v1560924153/alcatel-smartphones-einsteiger-mittelklasse-neu-3m.jpg"
                                                                            alt=""></div>
                                                                    <div class="bbb_viewed_content text-center">
                                                                        <div class="bbb_viewed_price">
                                                                            ₹12225<span>₹13300</span></div>
                                                                        <div class="bbb_viewed_name"><a href="#">Alkatel
                                                                                Phone</a></div>
                                                                    </div>
                                                                    <ul class="item_marks">
                                                                        <li class="item_mark item_discount">-25%
                                                                        </li>
                                                                        <li class="item_mark item_new">new</li>
                                                                    </ul>
                                                                </div>
                                                            </div>
                                                            <div class="owl-item">
                                                                <div
                                                                    class="bbb_viewed_item d-flex flex-column align-items-center justify-content-center text-center">
                                                                    <div class="bbb_viewed_image"><img
                                                                            src="https://res.cloudinary.com/dxfq3iotg/image/upload/v1560924221/51_be7qfhil.jpg"
                                                                            alt=""></div>
                                                                    <div class="bbb_viewed_content text-center">
                                                                        <div class="bbb_viewed_price">₹30079</div>
                                                                        <div class="bbb_viewed_name"><a href="#">Samsung
                                                                                LED</a></div>
                                                                    </div>
                                                                    <ul class="item_marks">
                                                                        <li class="item_mark item_discount">-25%
                                                                        </li>
                                                                        <li class="item_mark item_new">new</li>
                                                                    </ul>
                                                                </div>
                                                            </div>
                                                            <div class="owl-item">
                                                                <div
                                                                    class="bbb_viewed_item d-flex flex-column align-items-center justify-content-center text-center">
                                                                    <div class="bbb_viewed_image"><img
                                                                            src="https://res.cloudinary.com/dxfq3iotg/image/upload/v1560924241/8fbb415a2ab2a4de55bb0c8da73c4172--ps.jpg"
                                                                            alt=""></div>
                                                                    <div class="bbb_viewed_content text-center">
                                                                        <div class="bbb_viewed_price">₹22250</div>
                                                                        <div class="bbb_viewed_name"><a href="#">Samsung
                                                                                Mobile</a></div>
                                                                    </div>
                                                                    <ul class="item_marks">
                                                                        <li class="item_mark item_discount">-25%
                                                                        </li>
                                                                        <li class="item_mark item_new">new</li>
                                                                    </ul>
                                                                </div>
                                                            </div>
                                                            <div class="owl-item">
                                                                <div
                                                                    class="bbb_viewed_item is_new d-flex flex-column align-items-center justify-content-center text-center">
                                                                    <div class="bbb_viewed_image"><img
                                                                            src="https://res.cloudinary.com/dxfq3iotg/image/upload/v1560924275/images.jpg"
                                                                            alt=""></div>
                                                                    <div class="bbb_viewed_content text-center">
                                                                        <div class="bbb_viewed_price">₹1379</div>
                                                                        <div class="bbb_viewed_name"><a href="#">Huawei
                                                                                Power</a></div>
                                                                    </div>
                                                                    <ul class="item_marks">
                                                                        <li class="item_mark item_discount">-25%
                                                                        </li>
                                                                        <li class="item_mark item_new">new</li>
                                                                    </ul>
                                                                </div>
                                                            </div>
                                                            <div class="owl-item">
                                                                <div
                                                                    class="bbb_viewed_item discount d-flex flex-column align-items-center justify-content-center text-center">
                                                                    <div class="bbb_viewed_image"><img
                                                                            src="https://res.cloudinary.com/dxfq3iotg/image/upload/v1560924361/21HmjI5eVcL.jpg"
                                                                            alt=""></div>
                                                                    <div class="bbb_viewed_content text-center">
                                                                        <div class="bbb_viewed_price">
                                                                            ₹225<span>₹300</span></div>
                                                                        <div class="bbb_viewed_name"><a href="#">Sony
                                                                                Power</a></div>
                                                                    </div>
                                                                    <ul class="item_marks">
                                                                        <li class="item_mark item_discount">-25%
                                                                        </li>
                                                                        <li class="item_mark item_new">new</li>
                                                                    </ul>
                                                                </div>
                                                            </div>
                                                            <div class="owl-item">
                                                                <div
                                                                    class="bbb_viewed_item d-flex flex-column align-items-center justify-content-center text-center">
                                                                    <div class="bbb_viewed_image"><img
                                                                            src="https://res.cloudinary.com/dxfq3iotg/image/upload/v1560924241/8fbb415a2ab2a4de55bb0c8da73c4172--ps.jpg"
                                                                            alt=""></div>
                                                                    <div class="bbb_viewed_content text-center">
                                                                        <div class="bbb_viewed_price">₹13275</div>
                                                                        <div class="bbb_viewed_name"><a
                                                                                href="#">Speedlink Mobile</a></div>
                                                                    </div>
                                                                    <ul class="item_marks">
                                                                        <li class="item_mark item_discount">-25%
                                                                        </li>
                                                                        <li class="item_mark item_new">new</li>
                                                                    </ul>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane" id="kereta" role="tabpanel">5</div>
                            <div class="tab-pane" id="mobil" role="tabpanel">6</div>
                            <div class="tab-pane" id="bandara" role="tabpanel">7</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>

<script>
export default {
    name: "selection1View",
    
}

</script>

<style>
.upcomingfestivals {

    flex-basis: 42%;
}

.card-title {
    color: #db0075;
}

.card-text {
    color: #17E6E6;
}

.list-inline-item {
    color: #ffd700
}

.price {
    color: #9B1B30;
}

.btn-pink {
    background-color: #fcb2b2 !important;
}







@import url('https://fonts.googleapis.com/css?family=Montserrat:300,400,500,600,700,800,900|Rubik:300,400,500,700,900');

/* * {
margin: 0;
padding: 0;
-webkit-font-smoothing: antialiased;
-webkit-text-shadow: rgba(0, 0, 0, .01) 0 0 1px;
text-shadow: rgba(0, 0, 0, .01) 0 0 1px
}

body {
font-family: 'Rubik', sans-serif;
font-size: 14px;
font-weight: 400;
background: #eff6fa;
color: #000000
}

div {
display: block;
position: relative;
-webkit-box-sizing: border-box;
-moz-box-sizing: border-box;
box-sizing: border-box
} */




.bbb_viewed {
    padding-top: 51px;
    padding-bottom: 60px;
    background: #eff6fa
}

.bbb_main_container {
    background-color: #fff;
    padding: 11px;
}

.bbb_viewed_title_container {
    border-bottom: solid 1px #dadada
}

.bbb_viewed_title {
    margin-bottom: 16px;
    margin-top: 8px;

}

.bbb_viewed_nav_container {
    position: absolute;
    right: -5px;
    bottom: 14px
}

.bbb_viewed_nav {
    display: inline-block;
    cursor: pointer
}

.bbb_viewed_nav i {
    color: #dadada;
    font-size: 18px;
    padding: 5px;
    -webkit-transition: all 200ms ease;
    -moz-transition: all 200ms ease;
    -ms-transition: all 200ms ease;
    -o-transition: all 200ms ease;
    transition: all 200ms ease
}

.bbb_viewed_nav:hover i {
    color: #606264
}

.bbb_viewed_prev {
    margin-right: 15px
}

.bbb_viewed_slider_container {
    padding-top: 13px;
}

.bbb_viewed_item {
    width: 100%;
    background: #FFFFFF;
    border-radius: 2px;
    padding-top: 25px;
    padding-bottom: 25px;
    padding-left: 30px;
    padding-right: 30px
}

.bbb_viewed_image {
    width: 150px;
    height: 150px;
}

.bbb_viewed_image img {
    display: block;
    max-width: 100%
}

.bbb_viewed_content {
    width: 100%;
    margin-top: 25px
}

.bbb_viewed_price {
    font-size: 16px;
    color: #000000;
    font-weight: 500
}

.bbb_viewed_item.discount .bbb_viewed_price {
    color: #df3b3b
}

.bbb_viewed_price span {
    position: relative;
    font-size: 12px;
    font-weight: 400;
    color: rgba(0, 0, 0, 0.6);
    margin-left: 8px
}

.bbb_viewed_price span::after {
    display: block;
    position: absolute;
    top: 6px;
    left: -2px;
    width: calc(100% + 4px);
    height: 1px;
    background: #8d8d8d;
    content: ''
}

.bbb_viewed_name {
    margin-top: 3px
}

.bbb_viewed_name a {
    font-size: 14px;
    color: #000000;
    -webkit-transition: all 200ms ease;
    -moz-transition: all 200ms ease;
    -ms-transition: all 200ms ease;
    -o-transition: all 200ms ease;
    transition: all 200ms ease
}

.bbb_viewed_name a:hover {
    color: #0e8ce4
}

.item_marks {
    position: absolute;
    top: 18px;
    left: 18px
}

.item_mark {
    display: none;
    width: 36px;
    height: 36px;
    border-radius: 50%;
    color: #FFFFFF;
    font-size: 10px;
    font-weight: 500;
    line-height: 36px;
    text-align: center
}

.item_discount {
    background: #df3b3b;
    margin-right: 5px
}

.item_new {
    background: #0e8ce4
}

.bbb_viewed_item.discount .item_discount {
    display: inline-block
}

.bbb_viewed_item.is_new .item_new {
    display: inline-block
}
</style>