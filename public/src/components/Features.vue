<script setup>
const clientLogo ='/images/client-logos.png';
const heading ='HIGHLIGHTS';
const subtitle='Features We Love';

const features= [
    {
        title:'Simple',
        text:'Lorem ipsum dolor sit amet',

    },
    {
        title:'Customize',
        text:'Lorem ipsum dolor sit amet',

    },
    {
        title:'Secure',
        text:'Lorem ipsum dolor sit amet',

    }
    


]
</script>
<template>
<div class="client-logos my-5">
        <div class="container text-center">
            <img :src="clientLogo" alt="client logos" class="img-fluid">
        </div>
    </div>

    <div class="section light-bg" id="features">


        <div class="container">

            <div class="section-title">
                <small>{{ heading}}</small>
                <h3>{{ subtitle }}</h3>
            </div>


            <div class="row">
                <div class="col-12 col-lg-4">
                    <div class="card features">
                        <div class="card-body">
                            <div class="media">
                                <span class="ti-face-smile gradient-fill ti-3x mr-3"></span>
                                <div class="media-body">
                                    <h4 class="card-title">{{ features[0].title }}</h4>
                                    <p class="card-text">{{ features[0].text }} </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-lg-4">
                    <div class="card features">
                        <div class="card-body">
                            <div class="media">
                                <span class="ti-settings gradient-fill ti-3x mr-3"></span>
                                <div class="media-body">
                                    <h4 class="card-title">{{ features[1].title }}</h4>
                                    <p class="card-text">{{ features[1].text }} </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-lg-4">
                    <div class="card features">
                        <div class="card-body">
                            <div class="media">
                                <span class="ti-lock gradient-fill ti-3x mr-3"></span>
                                <div class="media-body">
                                    <h4 class="card-title">{{ features[2].title }}</h4>
                                    <p class="card-text">{{ features[2].text }} </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>



    </div>

</template>
<style scoped>
</style>