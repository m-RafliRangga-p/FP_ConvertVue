<template>
        <!-- Tentang Kami -->
        <div class="container-xxl py-5">
            <div class="container">
                <div class="row g-5">
                    <div class="col-lg-6" data-aos="fade-down" data-aos-delay="150" style="min-height: 400px;">
                        <div class="position-relative h-100">
                            <img class="img-fluid position-absolute w-100 h-100" src="../../public/assets/img/ponggok1.jpg" alt="" style="object-fit: cover;">
                        </div>
                    </div>
                    <div class="col-lg-6" data-aos="fade-down" data-aos-delay="250">
                        <h6 class="section-title bg-white text-start text-primary pe-3">Tentang Kami</h6>
                        <div class="animated-text">
                            Selamat datang di <span></span>
                        </div>
                        <p class="mb-4">Desa Ponggok adalah desa wisata yang berada di Kecamatan Polanharjo Kabupaten Klaten yang memiliki potensi alam</p>
                        <p class="mb-4">Potensi alam tersebut berupa sumber mata air jernih, segar dan melimpah dengan Umbul Ponggok sebagai objek wisata andalan</p>
                        <!-- <a class="btn btn-primary py-3 px-5 mt-2" href="../../public/assets/tentang_kami.html" data-aos="fade-down" data-aos-delay="250">Read More</a> -->
                        <router-link to="/about" class="btn btn-primary py-3 px-5 mt-2" data-aos="fade-down" data-aos-delay="250">Read More</router-link>
                    </div>
                </div>
            </div>
        </div>
    
        <!-- Kegiatan -->
        <div class="container-xxl py-5">
            <div class="container">
                <div class="text-center" data-aos="fade-down" data-aos-delay="150">
                    <h6 class="section-title bg-white text-center text-primary px-3">Kegiatan</h6>
                    <h1 class="mb-5">Kegiatan Terbaru</h1>
                </div>
                <div class="row g-4 justify-content-center">
                    <div class="col-lg-4 col-md-6" data-aos="fade-down" data-aos-delay="150">
                        <div class="package-item">
                            <div class="overflow-hidden">
                                <!-- image dummy ya -->
                                <img class="img-fluid" src="../../public/assets/img/ponggok2.jpg" alt="">
                            </div>
                            <div class="d-flex border-bottom">
                                <small class="flex-fill text-center border-end py-2"><i class="fa fa-map-marker-alt text-primary me-2"></i>Umbul Ponggok</small>
                                <small class="flex-fill text-center border-end py-2"><i class="fa fa-calendar-alt text-primary me-2"></i> 3 Januari 2023</small>
                            </div>
                            <div class="text-center p-4">
                                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Provident voluptates eligendi expedita reprehenderit qui, inventore voluptatem esse quo possimus sit illum cumque quisquam laudantium nihil autem reiciendis, vitae sed. Enim.</p>
                                <div class="d-flex justify-content-center mb-2">
                                    <a href="#" class="btn btn-sm btn-primary px-3" style="border-radius: 35px">Read More</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6" data-aos="fade-down" data-aos-delay="250">
                        <div class="package-item">
                            <div class="overflow-hidden">
                                <img class="img-fluid" src="../../public/assets/img/ponggok2.jpg" alt="">
                            </div>
                            <div class="d-flex border-bottom">
                                <small class="flex-fill text-center border-end py-2"><i class="fa fa-map-marker-alt text-primary me-2"></i>Umbul e Yanto</small>
                                <small class="flex-fill text-center border-end py-2"><i class="fa fa-calendar-alt text-primary me-2"></i>4 May 2023</small>
                            </div>
                            <div class="text-center p-4">
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum minus numquam vitae iure nisi illum libero. Illum eaque fugiat iste mollitia deserunt tempore hic, temporibus quos ex? Labore, sint. Necessitatibus provident inventore quo ipsum harum aperiam recusandae neque perspiciatis deleniti?</p>
                                <div class="d-flex justify-content-center mb-2">
                                    <a href="#" class="btn btn-sm btn-primary px-3" style="border-radius: 35px;">Read More</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6" data-aos="fade-down" data-aos-delay="350">
                        <div class="package-item">
                            <div class="overflow-hidden">
                                <img class="img-fluid" src="../../public/assets/img/ponggok2.jpg" alt="">
                            </div>
                            <div class="d-flex border-bottom">
                                <small class="flex-fill text-center border-end py-2"><i class="fa fa-map-marker-alt text-primary me-2"></i>Umbul Anu</small>
                                <small class="flex-fill text-center border-end py-2"><i class="fa fa-calendar-alt text-primary me-2"></i>3 Juni 2023</small>
                            </div>
                            <div class="text-center p-4">
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis labore et sunt est neque incidunt exercitationem alias praesentium molestiae? Nesciunt laboriosam cum dolorem officia mollitia quibusdam dolores facilis nisi dignissimos.</p>
                                <div class="d-flex justify-content-center mb-2">
                                    <a href="#" class="btn btn-sm btn-primary px-3" style="border-radius: 35px">Read More</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    
        <!-- Destinasi -->
        <div class="container-xxl py-5 destination">
            <div class="container">
                <div class="text-center" data-aos="fade-down" data-aos-delay="150">
                    <h6 class="section-title bg-white text-center text-primary px-3">Destinasi</h6>
                    <h1 class="mb-5">Destinasi Populer</h1>
                </div>
                <div class="row g-3">
                    <div class="col-lg-7 col-md-6">
                        <div class="row g-3">
                            <div class="col-lg-12 col-md-12 wow zoomIn" data-wow-delay="0.1s" data-aos="zoomIn" data-aos-delay="150">
                                <a class="position-relative d-block overflow-hidden" href="../../public/assets/umbul/u_ponggok.html" target="_blank">
                                    <img class="img-fluid" src="../../public/assets/img/ponggok5.jpeg" alt="">
                                    <div class="bg-white text-danger fw-bold position-absolute top-0 start-0 m-3 py-1 px-2">Umbul Ponggok</div>
                                    <div class="bg-white text-primary fw-bold position-absolute bottom-0 end-0 m-3 py-1 px-2" style="border-radius: 20px;">Read More</div>
                                </a>
                            </div>
                            <div class="col-lg-6 col-md-12 wow zoomIn" data-wow-delay="0.3s" data-aos="zoomIn" data-aos-delay="250">
                                <a class="position-relative d-block overflow-hidden" href="../../public/assets/umbul/u_SiGedhang.html" target="_blank">
                                    <img class="img-fluid" src="../../public/assets/img/Gedhang/sigedang1.jpg" alt="">
                                    <div class="bg-white text-danger fw-bold position-absolute top-0 start-0 m-3 py-1 px-2">Umbul Kapiler</div>
                                    <div class="bg-white text-primary fw-bold position-absolute bottom-0 end-0 m-3 py-1 px-2" style="border-radius: 20px;">Read More</div>
                                </a>
                            </div>
                            <div class="col-lg-6 col-md-12 wow zoomIn" data-wow-delay="0.5s" data-aos="zoomIn" data-aos-delay="350">
                                <a class="position-relative d-block overflow-hidden" href="../../public/assets/umbul/u_SiGedhang.html" target="_blank">
                                    <img class="img-fluid" src="../../public/assets/img/Gedhang/sigedang3.jpg" alt="">
                                    <div class="bg-white text-danger fw-bold position-absolute top-0 start-0 m-3 py-1 px-2">Umbul SiGedhang</div>
                                    <div class="bg-white text-primary fw-bold position-absolute bottom-0 end-0 m-3 py-1 px-2" style="border-radius: 20px;">Read More</div>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-5 col-md-6 wow zoomIn" data-wow-delay="0.7s" data-aos="zoomIn" data-aos-delay="450" style="min-height: 350px;">
                        <a class="position-relative d-block h-100 overflow-hidden" href="../../public/assets/umbul/u_Besuki.html" target="_blank">
                            <img class="img-fluid position-absolute w-100 h-100" src="../../public/assets/img/Besuki/besuki4_up.jpg" alt="" style="object-fit: cover;">
                            <div class="bg-white text-danger fw-bold position-absolute top-0 start-0 m-3 py-1 px-2">Umbul Besuki</div>
                            <div class="bg-white text-primary fw-bold position-absolute bottom-0 end-0 m-3 py-1 px-2" style="border-radius: 20px;">Read More</div>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    
        <!-- Produk -->
        <div class="container-xxl py-5">
            <div class="container">
                <div class="text-center pb-4" data-aos="fade-down" data-aos-delay="150">
                    <h6 class="section-title bg-white text-center text-primary px-3">Produk</h6>
                    <h1 class="mb-5">Produk Kami</h1>
                </div>
                <div class="row gy-5 gx-4 justify-content-center">
                    <div class="col-lg-4 col-sm-6 text-center pt-4" data-aos="fade-down" data-aos-delay="250">
                        <div class="position-relative border border-primary pt-4 pb-4 px-4">
                            <div class="overflow-hidden">
                                <img class="img-fluid" src="../../public/assets/img/ponggok2.jpg" alt="">
                            </div>
                            <h5 class="mt-4">Bakpia</h5>
                            <hr class="w-25 mx-auto bg-primary mb-1">
                            <hr class="w-50 mx-auto bg-primary mt-0">
                            <p class="mb-0">Tempor erat elitr rebum clita dolor diam ipsum sit diam amet diam eos erat ipsum et lorem et sit sed stet lorem sit</p>
                        </div>
                    </div>
                    <div class="col-lg-4 col-sm-6 text-center pt-4" data-aos="fade-down" data-aos-delay="350">
                        <div class="position-relative border border-primary pt-4 pb-4 px-4">
                            <div class="overflow-hidden">
                                <img class="img-fluid" src="../../public/assets/img/ponggok2.jpg" alt="">
                            </div>
                            <h5 class="mt-4">Bakpia</h5>
                            <hr class="w-25 mx-auto bg-primary mb-1">
                            <hr class="w-50 mx-auto bg-primary mt-0">
                            <p class="mb-0">Tempor erat elitr rebum clita dolor diam ipsum sit diam amet diam eos erat ipsum et lorem et sit sed stet lorem sit</p>
                        </div>
                    </div>
                    <div class="col-lg-4 col-sm-6 text-center pt-4" data-aos="fade-down" data-aos-delay="450">
                        <div class="position-relative border border-primary pt-4 pb-4 px-4">
                            <div class="overflow-hidden">
                                <img class="img-fluid" src="../../public/assets/img/ponggok2.jpg" alt="">
                            </div>
                            <h5 class="mt-4">Bakpia</h5>
                            <hr class="w-25 mx-auto bg-primary mb-1">
                            <hr class="w-50 mx-auto bg-primary mt-0">
                            <p class="mb-0">Tempor erat elitr rebum clita dolor diam ipsum sit diam amet diam eos erat ipsum et lorem et sit sed stet lorem sit</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

         <!-- Testi Pengunjung (Carousels) -->
            <div class="container-xxl py-5 wow fadeInUp" data-wow-delay="0.1s">
                <div class="container">
                    <div class="text-center">
                        <h6 class="section-title bg-white text-center text-primary px-3">Testimonial</h6>
                        <h1 class="mb-5">Apa Kata Mereka?</h1>
                    </div>
                    <div class="owl-carousel testimonial-carousel position-relative">
                        <div class="testimonial-item bg-white text-center border p-4">
                            <img class="bg-white rounded-circle shadow p-1 mx-auto mb-3" src="../../public/assets/img/tim/dev.jpeg" style="width: 80px; height: 80px;">
                            <h5 class="mb-0">Yanto</h5>
                            <p>Solo, indonesia</p>
                            <p class="mb-0">Tempor erat elitr rebum at clita. Diam dolor diam ipsum sit diam amet diam et eos. Clita erat ipsum et lorem et sit.</p>
                        </div>
                        <div class="testimonial-item bg-white text-center border p-4">
                            <img class="bg-white rounded-circle shadow p-1 mx-auto mb-3" src="../../public/assets/img/tim/dev.jpeg" style="width: 80px; height: 80px;">
                            <h5 class="mb-0">Yaanti</h5>
                            <p>Klaten, inggris</p>
                            <p class="mt-2 mb-0">Tempor erat elitr rebum at clita. Diam dolor diam ipsum sit diam amet diam et eos. Clita erat ipsum et lorem et sit.</p>
                        </div>
                        <div class="testimonial-item bg-white text-center border p-4">
                            <img class="bg-white rounded-circle shadow p-1 mx-auto mb-3" src="../../public/assets/img/tim/dev.jpeg" style="width: 80px; height: 80px;">
                            <h5 class="mb-0">Samini</h5>
                            <p>Sragen, amerika</p>
                            <p class="mt-2 mb-0">Tempor erat elitr rebum at clita. Diam dolor diam ipsum sit diam amet diam et eos. Clita erat ipsum et lorem et sit.</p>
                        </div>
                        <div class="testimonial-item bg-white text-center border p-4">
                            <img class="bg-white rounded-circle shadow p-1 mx-auto mb-3" src="../../public/assets/img/tim/dev.jpeg" style="width: 80px; height: 80px;">
                            <h5 class="mb-0">Yuwi</h5>
                            <p>Karanganyar, belanda</p>
                            <p class="mt-2 mb-0">Tempor erat elitr rebum at clita. Diam dolor diam ipsum sit diam amet diam et eos. Clita erat ipsum et lorem et sit.</p>
                        </div>
                    </div>
                </div>
            </div>
        <a href="#" class="btn btn-lg btn-primary btn-lg-square back-to-top"><i class="bi bi-arrow-up"></i></a>
</template>