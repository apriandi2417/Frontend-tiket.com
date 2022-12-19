<template>
    <div class="container mt-3 p-4" style="text-align: left;">
        <h3>Ayo liburan ke destinasi menarik!</h3>
        <p>Ada berbagai pilihan penerbangan dengan harga spesial, lho. Jangan sampai kehabisan ya!</p>

        <div role="tabpanel">
            <!-- List group -->
            <div class="list-group list-group-horizontal position-relative overflow-auto mt-3" id="myList"
                role="tablist">
                <a class="list-group-item list-group-item-action me-3 rounded-pill text-nowrap w-auto active"
                    data-bs-toggle="list" href="#domestik" role="tab">Domestik</a>
                <a class="list-group-item list-group-item-action me-3 rounded-pill text-nowrap w-auto"
                    data-bs-toggle="list" href="#internasional" role="tab">Internasional</a>
            </div>

            <!-- Tab panes -->
            <div class="tab-content mt-3">
                <div class="tab-pane active" id="domestik" role="tabpanel">
                    <div class="container1">
                        <div class="carousel-view">
                            <button id="prev-btn" class="btn btn-light prev-btn" @click="prev()">
                                <fa icon="arrow-left" />
                            </button>
                            <div id="item-list" class="item-list">
                                <div class="card" v-for="x in 10" :key="x">
                                    <div class="position-relative">
                                        <img src="../assets/images/wisata1.webp" class="card-img-top " alt=""
                                            style="height: 200px;">
                                        <div
                                            class="position-absolute bottom-0 end-0 bg-danger text-nowrap rounded m-0 p-1">
                                            <p style="font-size: 10px;">Harga Spesial</p>
                                        </div>
                                    </div>

                                    <div class="card-body">
                                        <h6><strong>Jakarta - Denpasar Bali</strong></h6>
                                        <p class="card-text">26 Jan 2022</p>
                                        <p>Pesawat</p>
                                        <p>Ekonomi</p>
                                        <br>
                                        <p>Mulai dari</p>
                                        <h5 class="text-danger">IDR 700.000</h5>
                                    </div>
                                    <div class="position-absolute top-0 start-0 bg-white rounded m-2 p-1">
                                        <p>Sekali Jalan</p>
                                    </div>
                                </div>
                            </div>
                            <button id="next-btn" class="btn btn-light next-btn" @click="next()">
                                <fa icon="arrow-right" />
                            </button>
                        </div>
                    </div>
                </div>
                <div class="tab-pane" id="internasional" role="tabpanel">
                    <div class="carousel-view">
                        <button id="prev-btn" class="btn btn-light prev-btn" @click="prev1()">
                            <fa icon="arrow-left" />
                        </button>
                        <div id="item-list1" class="item-list">
                            <div class="card" v-for="x in 10" :key="x">
                                <div class="position-relative">
                                    <img src="../assets/images/wisata1.webp" class="card-img-top " alt=""
                                        style="height: 200px;">
                                    <div class="position-absolute bottom-0 end-0 bg-danger text-nowrap rounded m-0 p-1">
                                        <p style="font-size: 10px;">Harga Spesial</p>
                                    </div>
                                </div>
                                <div class="card-body">
                                    <h6><strong>Jakarta - Denpasar Bali</strong></h6>
                                    <p class="card-text">26 Jan 2022</p>
                                    <p>Pesawat</p>
                                    <p>Ekonomi</p>
                                    <br>
                                    <p>Mulai dari</p>
                                    <h5 class="text-danger">IDR 700.000</h5>
                                </div>
                                <div class="position-absolute top-0 start-0 bg-white rounded m-2 p-1">
                                    <p>Sekali Jalan</p>
                                </div>
                            </div>
                        </div>
                        <button id="next-btn" class="btn btn-light next-btn" @click="next1()">
                            <fa icon="arrow-right" />
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>


</template>

<script>

export default {
    name: 'selection2View',
    components: {

    },
    data() {
        return {
            itemWidth: 1140,
            padding: 90,
        }
    },
    methods: {
        prev() {
            const list = document.getElementById('item-list')
            list.scrollLeft -= this.itemWidth + this.padding
        },
        next() {
            const list = document.getElementById('item-list')
            list.scrollLeft += this.itemWidth + this.padding
        },prev1() {
            const list = document.getElementById('item-list1')
            list.scrollLeft -= this.itemWidth + this.padding
        },
        next1() {
            const list = document.getElementById('item-list1')
            list.scrollLeft += this.itemWidth + this.padding
        },
    }
}

</script>

<style scoped>
p {
    padding: 0px;
    margin: 0px;
}


.container1 {
    /* display: flex;
    overflow-x: scroll;
    padding: 24px;
    width: 100%;
    scroll-snap-type: x mandatory;
    scroll-padding: 24px;
    border-radius: 8px;
    gap: 12px; */
    display: flex;
    justify-content: center;
    align-items: center;
}

/* .container1 .item {
    flex: 0 0 100%;
    padding: 24px;
    border-radius: 8px;
    scroll-snap-align: start;
    width: 300px;
} */

.carousel-view {
    width: 100%;
    /* background-color: aqua; */
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
    /* padding: 44px 0; */
    transition: all 0.25s ease-in;
}

.carousel-view .item-list {
    /* background-color: tomato; */
    /* max-width: 60%; */
    width: 100%;
    margin: 0px -30px;
    /* padding: 50px 10px; */
    display: flex;
    gap: 20px;
    scroll-behavior: smooth;
    transition: all 0.25s ease-in;
    scrollbar-width: none;
    overflow: auto;
}

.item-list::-webkit-scrollbar {
    display: none;
}

.item {
    scroll-snap-align: center;
    min-width: 120px;
    height: 120px;
    background-color: deeppink;
    border-radius: 8px;
}

.card {
    scroll-snap-align: center;
    min-width: 228px;
    /* height: 120px; */
    /* background-color: deeppink; */
    border-radius: 8px;
}

.btn {
    z-index: 1;
}
</style>