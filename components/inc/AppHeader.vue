<template>
<div class='sticky-top'>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
        <a class="navbar-brand" href="/">
            <img src="/image/Star.png" alt="logo" class="logo_img" >
        </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <NuxtLink to="/" class="nav-link">Home </NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink to="/about" class="nav-link">About us</NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink to="/contact" class="nav-link">Contact us</NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink to="/services" class="nav-link">Services</NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink to="/formpage" class="nav-link">Form</NuxtLink>
                    </li>
                </ul> 
                </div>
                </div>
            </nav>
    </div>
</template>
<script>
export default {
    name: 'AppHeader'
}
</script>
<style>
.logo_img{
    width: 40px;
    height: 35px;
}
.customNav{
     text-color:#000;
     display: flex;
     align-item:center;
     justify-content:center;
     
}
</style>