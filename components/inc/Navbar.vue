<template>
<nav class="navbar navbar-expand-lg bg-white shadow fixed-top">
<div class="container">
<NuxtLink class="navbar-brand text-capitalize" to="/">komunitas badminton</NuxtLink>
<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
</button>
<div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
    <li class="nav-item">
        <NuxtLink class="nav-link text-capitalize" to="/">home</NuxtLink>
    </li>
    <li class="nav-item">
        <NuxtLink class="nav-link text-capitalize" to="/about">about</NuxtLink>
    </li>
    <li class="nav-item">
        <NuxtLink class="nav-link text-capitalize" to="/member">member</NuxtLink>
    </li>
    <li class="nav-item">
        <NuxtLink class="nav-link text-capitalize" to="/contact">contact</NuxtLink>
    </li>
    </ul>
</div>
</div>
</nav>
</template>

<script>
export default {
    name:'Navbar'
}
</script>

<style>
a.nuxt-link-active {
    font-weight: normal;
}
a.nuxt-link-exact-active.navbar-brand{
    border: none;
}
/* exact link will show the primary color for only the exact matching link */
a.nuxt-link-exact-active {
    color: #000;
    border-bottom: 1px solid black;
}
</style>