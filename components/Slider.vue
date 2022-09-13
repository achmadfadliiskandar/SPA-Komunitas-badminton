<template>
<div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
<div class="carousel-indicators">
<button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
<button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
<button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
</div>
<div class="carousel-inner">
<div class="carousel-item active">
    <img src="/images/slider1.jpg" class="d-block w-100 gambar" alt="gambar1">
    <div class="carousel-caption d-none d-md-block">
    <h5>Pemain Indonesia yang Menjadi juara 3 olimpiade tokyo th 2020</h5>
    <p>kategori : tunggal putra</p>
    </div>
</div>
<div class="carousel-item">
    <img src="/images/slider2.jpg" class="d-block w-100 gambar" alt="gambar2">
    <div class="carousel-caption d-none d-md-block">
    <h5>Pemain Denmark yang dijuluki sebagai monster/alien</h5>
    <p>kategori : tunggal putra</p>
    </div>
</div>
<div class="carousel-item">
    <img src="/images/slider3.jpg" class="d-block w-100 gambar" alt="gambar3">
    <div class="carousel-caption d-none d-md-block">
    <h5>Pemain Ganda Putri juara 1 olimpiade tokyo 2020</h5>
    <p>kategori: ganda putri</p>
    </div>
</div>
</div>
<button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
<span class="carousel-control-prev-icon" aria-hidden="true"></span>
<span class="visually-hidden">Previous</span>
</button>
<button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
<span class="carousel-control-next-icon" aria-hidden="true"></span>
<span class="visually-hidden">Next</span>
</button>
</div>
</template>

<script>
export default {
    name:'slider'
}
</script>

<style>
.gambar{
    height:400px;
}
</style>