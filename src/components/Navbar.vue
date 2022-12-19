<template>
    <div class="header position-relative">
        <nav class="navbar navbar-expand-lg ">
            <div class="container">
                <a class="navbar-brand" href="#">
                    <img src="../assets/images/logo.webp" alt=""
                        style="object-fit: contain; width: 128px; height: 32px;">
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link" href="#">Jadi Partner tiket.com</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Elite Rewards</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Cek Order</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                                aria-expanded="false">
                                IDR
                            </a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another action</a></li>
                                <li>
                                    <hr class="dropdown-divider">
                                </li>
                                <li><a class="dropdown-item" href="#">Something else here</a></li>
                            </ul>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Masuk</a>
                        </li>
                        <li class="nav-item bg-primary">
                            <a class="nav-link" href="#">Daftar</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>


        <div class="position-absolute top-50 start-50 translate-middle text-white">
            <div>
                <h3>Hai kamu, <strong>mau ke mana?</strong></h3>
                <div class="input-group has-search mb-3 ">
                    <!-- <span class="form-control-feedback" id="addon-wrapping"><fa icon="search"/></span> -->
                    <input type="text" class="form-control " placeholder="Username" aria-label="Username"
                        aria-describedby="basic-addon1">
                </div>
            </div>
            <div class="menu">
                <ul>
                    <li>
                        <a href="" style="text-decoration: none; color: white;">
                            <div class="bg-white p-3 rounded-circle bg-opacity-25 mb-2">
                                <img src="../assets/images/ikon/pesawat.webp" class="rounded-circle"
                                    style="width: 50px;" alt="Avatar" />
                            </div>
                            <p>Pesawat</p>
                        </a>
                    </li>
                    <li>
                        <a href="" style="text-decoration: none; color: white;">
                            <div class="bg-white p-3 rounded-circle bg-opacity-25 mb-2">
                                <img src="../assets/images/ikon/hotel.webp" class="rounded-circle" style="width: 50px;"
                                    alt="Avatar" />
                            </div>
                            <p>Hotel</p>
                        </a>
                    </li>
                    <li>
                        <a href="" style="text-decoration: none; color: white;">
                            <div class="bg-white p-3 rounded-circle bg-opacity-25 mb-2">
                                <img src="../assets/images/ikon/to_do.webp" class="rounded-circle" style="width: 50px;"
                                    alt="Avatar" />
                            </div>
                            <p>To Do</p>
                        </a>
                    </li>
                    <li>
                        <a href="" style="text-decoration: none; color: white;">
                            <div class="bg-white p-3 rounded-circle bg-opacity-25 mb-2">
                                <img src="../assets/images/ikon/kereta.webp" class="rounded-circle" style="width: 50px;"
                                    alt="Avatar" />
                            </div>
                            <p>Kereta</p>
                        </a>
                    </li>
                    <li>
                        <a href="" style="text-decoration: none; color: white;">
                            <div class="bg-white p-3 rounded-circle bg-opacity-25 mb-2">
                                <img src="../assets/images/ikon/mobil.webp" class="rounded-circle" style="width: 50px;"
                                    alt="Avatar" />
                            </div>
                            <p>Sewa Mobil</p>
                        </a>
                    </li>
                    <li>
                        <a href="" style="text-decoration: none; color: white;">
                            <div class="bg-white p-3 rounded-circle bg-opacity-25 mb-2">
                                <img src="../assets/images/ikon/event.webp" class="rounded-circle" style="width: 50px;"
                                    alt="Avatar" />
                            </div>
                            <p>Event</p>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'NavbarView',

}

</script>

<style scoped>
.header {
    background-image: url('../assets/images/navbar_background.webp');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    margin: 0px;
    padding: 0px;
    width: 100%;
    height: 75vh;
    /* background-color: aquamarine; */
}

.nav-link {
    color: white;
}

.nav-item {
    padding: 2px 10px;
    border-radius: 10px;
}

.menu {
    width: fit-content;
}

.menu ul {
    list-style: none;
    width: fit-content;
}

.menu ul li {
    float: left;
    padding-left: 30px;
    width: fit-content;
}

/* .has-search .form-control-feedback {
    position: absolute;
    z-index: 2;
    display: block;
    width: 2.375rem;
    height: 2.375rem;
    line-height: 2.375rem;
    text-align: center;
    pointer-events: none;
    color: #aaa;
    padding: 18px;
} */
.form-control {
    padding: 20px;
    border-radius: 100px;
    padding-left: 3.375rem;
}
</style>