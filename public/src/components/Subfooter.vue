<script setup>
import Contact from './Contact.vue';
const heading ='Download Anywhere';
const subheading='Available for all major mobile and desktop platforms. Rapidiously visualize optimal ROI rather than enterprise-wide methods of empowerment';
const images= [
    {
        src:'/images/appleicon.png',
        title:'AppStore',
        alt:'icon',

    },
    {
        src:'/images/playicon.png',
        title:'Google Play',
        alt:'icon',

    },
    
    


]

</script>
<template>
 <div class="section bg-gradient">
        <div class="container">
            <div class="call-to-action">

                <div class="box-icon"><span class="ti-mobile gradient-fill ti-3x"></span></div>
                <h2>{{ heading }}</h2>
                <p class="tagline">{{ subheading }}</p>
                <div class="my-4">

                    <a href="#" class="btn btn-light"><img v-bind="images[0]">{{ images[0].title }}</a>
                    <a href="#" class="btn btn-light"><img v-bind="images[0]"> {{ images[1].title }}</a>
                </div>
            </div>
        </div>

    </div>
    <Contact/>
  
</template>
<style scoped></style>