<template>
<div>
    <header>
        <div class="container-fluid text-sm-center text-white p-5 bg-secondary">
            <h1 class="display-2 pt-5">Member</h1>
            <p class="lead">Anggota Yang ada Forum Ini</p>
        </div>
    </header>
    <div class="container my-3">
        <h2>Sambutan Pelatih</h2>
        <div class="row">
            <div class="col-sm-6">
                <img src="/images/pelatih.PNG" style="height:300px;width:100%;" alt="">
            </div>
            <div class="col-sm-6">
                <br>    
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam ad rem voluptas culpa voluptatum animi hic illo harum voluptate, ea, tempore quo! Possimus, nisi quia tempora officia, molestias accusantium aliquid necessitatibus sit consectetur, cumque totam. Assumenda repellendus non quo. Reiciendis culpa doloremque eum impedit cum consectetur accusamus eos incidunt atque! Ratione, eos magni. Repellat dignissimos repellendus corrupti iusto amet velit perferendis soluta vel, eos neque asperiores modi pariatur quod voluptas quia nulla? Deleniti, tempore. Delectus architecto et soluta possimus itaque ut assumenda minima sapiente excepturi veritatis, asperiores omnis a? Sequi commodi qui eaque rem sapiente ipsa nulla impedit unde tempore!</p>
            </div>
        </div>
    </div>
    <div class="bg-light">
        <hr>
        <div class="container">
        <h3>Member</h3>
        <div class="row">
            <div class="col-sm-4">
                <div class="card" style="width: 100%;">
                <img src="/images/malehoy.PNG" class="card-img-top" style="height:200px;" alt="rizky">
                <div class="card-body">
                    <h5 class="card-title">Rizky Andiansah</h5>
                    <p class="card-text">Tangan : Kanan</p>
                    <a href="#" class="btn btn-primary">Lihat Tentang Saya</a>
                </div>
                </div>
            </div>
            <div class="col-sm-4">
                <div class="card" style="width: 100%;">
                <img src="/images/akhdan.PNG" class="card-img-top" style="height:200px;" alt="rizky">
                <div class="card-body">
                    <h5 class="card-title">Akhdan Nadief Biantara</h5>
                    <p class="card-text">Tangan : Kanan</p>
                    <a href="#" class="btn btn-primary">Lihat Tentang Saya</a>
                </div>
                </div>
            </div>
            <div class="col-sm-4">
                <div class="card" style="width: 100%;">
                <img src="/images/syafiq.PNG" class="card-img-top" style="height:200px;" alt="rizky">
                <div class="card-body">
                    <h5 class="card-title">Syafiq Irham Sambara Hafidz</h5>
                    <p class="card-text">Tangan : Kanan</p>
                    <a href="#" class="btn btn-primary">Lihat Tentang Saya</a>
                </div>
                </div>
            </div>
            <div class="col-sm-4 my-3">
                <div class="card" style="width: 100%;">
                <img src="/images/fadlan.PNG" class="card-img-top" style="height:200px;" alt="rizky">
                <div class="card-body">
                    <h5 class="card-title">Muhammad Fadlan Iskandar</h5>
                    <p class="card-text">Tangan : Kanan</p>
                    <a href="#" class="btn btn-primary">Lihat Tentang Saya</a>
                </div>
                </div>
            </div>
            <div class="col-sm-4 my-3">
                <div class="card" style="width: 100%;">
                <img src="/images/rani.jpg" class="card-img-top" style="height:200px;" alt="rani">
                <div class="card-body">
                    <h5 class="card-title">Maharani Faizah Iskandar</h5>
                    <p class="card-text">Tangan : Kanan</p>
                    <a href="#" class="btn btn-primary">Lihat Tentang Saya</a>
                </div>
                </div>
            </div>
            <div class="col-sm-4 my-3">
                <div class="card" style="width: 100%;">
                <img src="/images/faiz.jpg" class="card-img-top" style="height:200px;" alt="faiz">
                <div class="card-body">
                    <h5 class="card-title">Muhammad Faiz Iskandar</h5>
                    <p class="card-text">Tangan : Kanan</p>
                    <a href="#" class="btn btn-primary">Lihat Tentang Saya</a>
                </div>
                </div>
            </div>
            <div class="col-sm-4 my-3">
                <div class="card" style="width: 100%;">
                <img src="/images/fadli.PNG" class="card-img-top" style="height:200px;" alt="rizky">
                <div class="card-body">
                    <h5 class="card-title">Achmad Fadli Iskandar</h5>
                    <p class="card-text">Tangan : Kanan</p>
                    <a href="#" class="btn btn-primary">Lihat Tentang Saya</a>
                </div>
                </div>
            </div>
        </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
name: 'member',
head() {
    return {
    title: "Member",
    meta: [
        {
        hid: 'description',
        name: 'description',
        content: 'Komunitas Badminton - Member'
        },
        {
        hid: 'keywords',
        name: 'keywords',
        content: 'Member / Anggota Komunitas Badminton Kota Depok'
        }
    ]
    }
}
}
</script>
