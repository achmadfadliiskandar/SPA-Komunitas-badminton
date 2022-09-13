<template>
<div>
    <header>
        <div class="container-fluid text-sm-center text-white p-5 bg-dark">
            <h1 class="display-2 pt-5">About</h1>
            <p class="lead">Tentang Dari Forum Ini</p>
        </div>
    </header>
    <div class="container my-3">
        <h2 class="my-3">Cerita Lengkap</h2>
        <div class="row my-3 text-justify">
            <div class="col-sm-6">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam quis perspiciatis quasi eveniet sunt aliquid id laboriosam veniam illo odit dolorum in perferendis eum, sit, quidem iste error non est architecto magni animi omnis ex autem. Labore quod, corrupti quo reiciendis atque optio repellat expedita aperiam quam, voluptatem vitae harum animi, voluptatum ratione laborum necessitatibus aliquid. Ipsa, quisquam maxime. Voluptas fugiat facere, error nobis unde commodi labore nesciunt saepe neque ex autem culpa fugit nihil quaerat, sequi illo tempore, exercitationem quisquam illum soluta accusantium deserunt. Voluptates ut ad perferendis, suscipit assumenda quia iusto unde quibusdam enim adipisci consectetur facilis accusamus, corrupti tenetur harum labore, reiciendis dolorum veritatis deserunt! Reprehenderit laudantium possimus unde explicabo aliquam, exercitationem sunt adipisci vel ab, dolore facilis sed accusamus eligendi molestias illum amet numquam voluptates nam doloremque culpa impedit facere. Molestiae nesciunt id cupiditate sequi expedita perspiciatis, illum optio odit mollitia sed, voluptatibus, incidunt aspernatur similique!</div>
            <div class="col-sm-6">Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore quam, officiis rem iusto illo libero at consequuntur unde tempora omnis sapiente, dolore facere velit odio assumenda necessitatibus aperiam, reprehenderit alias deserunt eum. Atque blanditiis voluptas vel incidunt veniam officia minima distinctio iusto illum quasi. Porro dicta magnam numquam at, quod reiciendis atque? Ab iure libero aut nihil ea neque perspiciatis dolorum itaque? Dolorem dolor officia, accusantium odit eum reprehenderit nisi sapiente laboriosam similique in sunt voluptas debitis ratione quod repellat, temporibus tenetur incidunt perspiciatis ipsum unde. Impedit, eaque modi. Qui voluptate sit amet reiciendis distinctio enim possimus ad quibusdam ex ea. Laborum laboriosam incidunt nemo eveniet facere voluptatem. Maxime eveniet dolor fugiat dolore adipisci soluta sunt maiores facere, culpa temporibus perferendis harum numquam tempora laboriosam hic id consectetur dolores est. Vitae nostrum quidem ratione quod sit harum modi nam optio? Voluptas voluptatem corporis doloribus ea doloremque, quibusdam aspernatur beatae? Facilis?</div>
        </div>
    </div>
    <div class="bg-light">
        <hr>
        <div class="container">
        <h2>Apa Yang Kami Lakukan</h2>
        <p>Main Bareng / Mabar</p>
        <div class="progress">
            <div class="progress-bar bar-striped" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">25%</div>
        </div>
        <p>Latihan Bersama</p>
        <div class="progress">
            <div class="progress-bar bar-striped bg-danger" role="progressbar" style="width: 50%;" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">50%</div>
        </div>
        <p>Buka Puasa Bersama / Bukber</p>
        <div class="progress">
            <div class="progress-bar bar-striped bg-success" role="progressbar" style="width: 75%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">75%</div>
        </div>
        <p>Memberikan Informasi Badminton yang layak</p>
        <div class="progress">
            <div class="progress-bar bar-striped bg-info" role="progressbar" style="width: 100%;" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100">100%</div>
        </div>
        <br>
        <br>
        </div>
    </div>
</div>
</template>

<script>
export default {
name: 'about',
head() {
return {
title: "About",
meta: [
    {
    hid: 'description',
    name: 'description',
    content: 'Komunitas Badminton - About'
    },
    {
    hid: 'keywords',
    name: 'keywords',
    content: 'Tentang Komunitas Badminton Kota Depok'
    }
]
}
}
}
</script>
