<script setup>
import Carousel from './Carousel.vue';

const appLogo ='/images/logo.png';
const headerImage='/images/iphonex.png';
const heading ='Mobile App';
const subheading='The one and only solution for any kind of mobile app  needs.';
</script>
<template>
   <div class="nav-menu fixed-top">
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <nav class="navbar navbar-dark navbar-expand-lg">
                        <a class="navbar-brand" href="index.html"><img :src="appLogo" class="img-fluid" alt="logo"></a> <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar" aria-controls="navbar" aria-expanded="false" aria-label="Toggle navigation"> <span class="navbar-toggler-icon"></span> </button>
                        <div class="collapse navbar-collapse" id="navbar">
                            <ul class="navbar-nav ml-auto">
                                <li class="nav-item"> <a class="nav-link active" href="#home">HOME <span class="sr-only">(current)</span></a> </li>
                                <li class="nav-item"> <a class="nav-link" href="#features">FEATURES</a> </li>
                                <li class="nav-item"> <a class="nav-link" href="#pricing">PRICING</a> </li>
                                <li class="nav-item"> <a class="nav-link" href="#contact">CONTACT</a> </li>
                            </ul>
                        </div>
                    </nav>
                </div>
            </div>
        </div>
    </div>


    <header class="bg-gradient" id="home">
        <div class="container mt-5">
            <h1>{{ heading }}</h1>
            <p class="tagline">{{ subheading }} </p>
        </div>
        <div class="img-holder mt-3"><img :src="headerImage" alt="phone" class="img-fluid"></div>
    </header>

</template>

<style scoped>
</style>