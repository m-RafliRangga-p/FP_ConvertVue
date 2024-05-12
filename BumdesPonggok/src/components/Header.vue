<template>
    <!-- Topbar -->
    <div class="container-fluid bg-dark px-5 d-none d-lg-block">
        <div class="row gx-0">
            <div class="col-lg-8 text-center text-lg-start mb-2 mb-lg-0">
                <div class="d-inline-flex align-items-center" style="height: 45px;">
                    <small class="me-3 text-light"><i class="fa fa-map-marker-alt me-2"></i>alamat</small>
                    <small class="me-3 text-light"><i class="fa fa-phone-alt me-2"></i>notelf</small>
                    <small class="text-light"><i class="fa fa-envelope-open me-2"></i>email</small>
                </div>
            </div>
            <div class="col-lg-4 text-center text-lg-end">
                <div class="d-inline-flex align-items-center" style="height: 45px;">
                    <a class="btn btn-sm btn-outline-light btn-sm-square rounded-circle me-2" href=""><i class="fab fa-twitter fw-normal"></i></a>
                    <a class="btn btn-sm btn-outline-light btn-sm-square rounded-circle me-2" href=""><i class="fab fa-facebook-f fw-normal"></i></a>
                    <a class="btn btn-sm btn-outline-light btn-sm-square rounded-circle me-2" href=""><i class="fab fa-linkedin-in fw-normal"></i></a>
                    <a class="btn btn-sm btn-outline-light btn-sm-square rounded-circle me-2" href=""><i class="fab fa-instagram fw-normal"></i></a>
                    <a class="btn btn-sm btn-outline-light btn-sm-square rounded-circle" href=""><i class="fab fa-youtube fw-normal"></i></a>
                </div>
            </div>
        </div>
    </div>

    <!-- Navbar & Hero Start -->
    <div class="container-fluid position-relative p-0">
        <nav class="navbar navbar-expand-lg navbar-light px-4 px-lg-5 py-3 py-lg-0">
            <router-link to="/" class="navbar-brand p-0">
                <img src="../../public/assets/img/BUMDES TIRTA MANDIRI.png" alt="Logo">
            </router-link>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse">
                <span class="fa fa-bars"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarCollapse">
                <div class="navbar-nav ms-auto py-0">
                    <!-- <a href="index.html" class="nav-item nav-link active">Home</a> -->
                    <router-link to="/" class="nav-item nav-link active">Home</router-link>
                    <!-- <a href="./tentang_kami.html" >Tentang Kami</a> -->
                    <router-link to="/about" class="nav-item nav-link">Tentang Kami</router-link>
                    <div class="nav-item dropdown">
                        <a href="#" class="nav-link dropdown-toggle" data-bs-toggle="dropdown">Wisata</a>
                        <div class="dropdown-menu m-0">
                            <a href="../../public/assets/umbul/u_ponggok.html" target="_blank" class="dropdown-item">Umbul Ponggok</a>
                            <a href="../../public/assets/umbul/u_Besuki.html" target="_blank" class="dropdown-item">Umbul Besuki</a>
                            <a href="../../public/assets/umbul/u_SiGedhang.html" target="_blank" class="dropdown-item">Umbul SiGedhang</a>
                        </div>
                    </div>
                    <!-- <a href="./tim.html" class="nav-item nav-link">Developer</a> -->
                    <router-link to="/tim" class="nav-item nav-link">Developer</router-link>
                </div>
            </div>
        </nav>

        <div class="container-fluid bg-primary py-5 mb-5 hero-header">
            <div class="container py-5">
                <div class="row justify-content-center py-5">
                    <div class="col-lg-10 pt-lg-5 mt-lg-5 text-center">
                        <h1 class="display-3 text-white mb-3 animated slideInDown">Selamat Datang di Desa Ponggok</h1>
                        <p class="fs-4 text-white mb-4 animated slideInDown">Tempor erat elitr rebum at clita diam amet diam et eos erat ipsum lorem sit</p>
                    </div>
                </div>
            </div>
        </div>
    </div>    
</template>