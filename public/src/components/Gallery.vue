<script setup>
const heading ='App Screenshots';
const subheading='GALLERY';
const images= [
    {
        src:'/images/screen1.jpg',
        title:'Lorem ipsum dolor sit amet',
        alt:'Lorem ipsum dolor',

    },
    {
        src:'/images/screen2.jpg',
        title:'Lorem ipsum dolor sit amet',
        alt:'Lorem ipsum dolor',

    },
    {
        src:'/images/screen3.jpg',
        title:'Lorem ipsum dolor sit amet',
        alt:'Lorem ipsum dolor',

    },
    {
        src:'/images/screen1.jpg',
        title:'Lorem ipsum dolor sit amet',
        alt:'Lorem ipsum dolor',

    },
    


]
</script>
<template>
    <div class="section light-bg" id="gallery">
        <div class="container">
            <div class="section-title">
                <small>{{ subheading }}</small>
                <h3>{{ heading }}</h3>
            </div>

            <div class="img-gallery owl-carousel owl-theme">
                <img v-bind="images[0]">
                <img v-bind="images[1]">
                <img v-bind="images[2]">
                <img v-bind="images[3]">



               
            </div>

        </div>

    </div>


</template>
<style scoped></style>