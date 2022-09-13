<template>
<div>
  <Slider/>
<div class="container">
  <h1 class="text-center">Berita / Informasi Seputar Badminton</h1>
  <p class="text-center">Postingan yang kami buat</p>
  <div class="row text-justify pt-3 pb-3">
    <div class="col-sm-4">
      <div class="card" style="width: 100%;">
        <img src="/images/slider1.jpg" class="card-img-top" alt="ginting">
        <div class="card-body">
          <h5 class="card-title">Tunggal Putra Indonesia Berhasil Jadi Juara 3 di kejuaraan olimpiade tahun 2020</h5>
          <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati fugiat harum rem enim ut minus accusamus labore! Quis, assumenda voluptatum obcaecati mollitia nam exercitationem praesentium?</p>
          <a href="#" class="btn btn-primary">Read More</a>
        </div>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="card" style="width: 100%;">
        <img src="/images/slider2.jpg" class="card-img-top" alt="ginting">
        <div class="card-body">
          <h5 class="card-title">Tunggal Putra Denmark Berhasil Jadi Juara 1 di kejuaraan olimpiade tahun 2020</h5>
          <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati fugiat harum rem enim ut minus accusamus labore! Quis, assumenda voluptatum obcaecati mollitia nam exercitationem praesentium?</p>
          <a href="#" class="btn btn-primary">Read More</a>
        </div>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="card" style="width: 100%;">
        <img src="/images/slider3.jpg" class="card-img-top" alt="ginting" style="height:235px;">
        <div class="card-body">
          <h5 class="card-title">Ganda Putri Indonesia Berhasil Jadi Juara 1 di kejuaraan olimpiade tahun 2020</h5>
          <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo rerum temporibus corporis, possimus qui pariatur autem neque soluta voluptas nemo. Veritatis in tempore vero dolor!</p>
          <a href="#" class="btn btn-primary">Read More</a>
        </div>
      </div>
    </div>
  </div>
</div>
<div class="col-lg-12 pt-3 pb-3 bg-light">
    <section>
      <div class="container">
        <h1 class="text-center">5 Pemain Rangking teratas bedasarkan kategori di dunia</h1>
        <Table />
      </div>
    </section>
  </div>
</div>
</template>

<script>
import Slider from '../components/Slider.vue';
import Table from '../components/Table.vue';
export default {
name: 'IndexPage',
components:
Slider,
Table,
head() {
      return {
        title: "Halaman Utama",
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Komunitas Badminton - Halaman Utama'
          },
          {
            hid: 'keywords',
            name: 'keywords',
            content: 'Komunitas Badminton Kota Depok'
          }
        ]
      }
    }
}
</script>
