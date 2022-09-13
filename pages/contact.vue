<template>
<div>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <header>
        <div class="container-fluid text-sm-center text-white p-5 bg-warning">
            <h1 class="display-2 pt-5">Contact</h1>
            <p class="lead">Silahkan Hubungi Nomor di bawah ini</p>
        </div>
    </header>
    <div class="container">
        <h2 class="my-3">Sosial Media</h2>
        <div class="row">
            <div class="col-sm-4">
                <i class="fa fa-whatsapp" style="font-size:48px;color:green"></i>
                <br>
                <button class="btn btn-success my-3">Whatsapp</button>
            </div>
            <div class="col-sm-4">
                <i class="fa fa-instagram" style="font-size:48px;color:purple"></i>
                <br>
                <button class="btn btn-primary my-3">Instagram</button>
            </div>
            <div class="col-sm-4">
                <i class="fa fa-facebook" style="font-size:48px;color:blue"></i>
                <br>
                <button class="btn btn-info my-3">facebook</button>
            </div>
        </div>
        <hr>
        <div>
            <h2>Maps</h2>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3965.1122115675557!2d106.8167655143422!3d-6.37951416417626!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69edd116252103%3A0x950e12f4d63456c4!2sGOR%20GLORIA!5e0!3m2!1sid!2sid!4v1663040839234!5m2!1sid!2sid" style="border:0;width:100%;height:350px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
    </div>
    <div class="bg-light">
        <hr>
    <div class="container">
        <h2>Form</h2>
        <p class="text-capitalize">jika anda ingin join ke Komunitas Badminton silahkan isi form di bawah ini terima kasih</p>
        <form>
        <div class="mb-3">
            <label for="nama" class="form-label">Nama</label>
            <input type="text" class="form-control" id="exampleInputEmail1" aria-describedby="nama" name="nama">
        </div>
        <div class="mb-3">
            <label for="exampleInputEmail1" class="form-label">Email</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            <div id="emailHelp" class="form-text">yang di isi email aktif ya</div>
        </div>
        <div class="mb-3">
            <label for="alamat" class="form-label">Alamat</label>
            <input type="text" class="form-control" id="exampleInputEmail1" aria-describedby="alamat" name="alamat">
        </div>
        <div class="mb-3">
            <label for="nohp" class="form-label">Nomor hp</label>
            <input type="number" class="form-control" id="exampleInputEmail1" aria-describedby="nohp" name="nohp">
        </div>
        <label for="alasan" class="form-label">Keterangan</label>
        <div class="mb-3">
            <textarea name="alasan" class="form-control" id="alasan" cols="30" rows="10"></textarea>
            <div id="emailHelp" class="form-text">jelaskan alasan anda mengapa anda ingin bergabung di komunitas ini</div>
        </div>
        <button type="submit" class="btn btn-primary my-3">Submit</button>
        </form>
    </div>
    </div>
</div>
</template>

<script>
export default {
name: 'contact',
head() {
    return {
    title: "Contact",
    meta: [
        {
        hid: 'description',
        name: 'description',
        content: 'Komunitas Badminton - Contact'
        },
        {
        hid: 'keywords',
        name: 'keywords',
        content: 'Contact Komunitas Badminton Kota Depok'
        }
    ]
    }
}
}
</script>
