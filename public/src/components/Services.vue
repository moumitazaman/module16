<script setup>
const launchImage ='/images/dualphone.png';
const heading ='Launch your App';
const subheading='Lorem ipsum dolor sit amet consectetur';

const functionalities= [
    {
        title:'Create an Account',
        text:'Lorem ipsum dolor sit amet',

    },
    {
        title:'Share with Friends',
        text:'Lorem ipsum dolor sit amet',

    },
    {
        title:'Enjoy Your Life',
        text:'Lorem ipsum dolor sit amet',

    }
    


]
const functionImage='/images/iphonex.png';
</script>
<template>
<div class="section">

<div class="container">
    <div class="row">
        <div class="col-md-6">
            <img :src="launchImage" alt="dual phone" class="img-fluid">
        </div>
        <div class="col-md-6 d-flex align-items-center">
            <div>
                <div class="box-icon"><span class="ti-rocket gradient-fill ti-3x"></span></div>
                <h2>{{ heading }}</h2>
                <p class="mb-4">{{ subheading }} </p>
                <a href="#" class="btn btn-primary">Read more</a></div>
        </div>
    </div>

</div>

</div>
<!-- // end .section -->


<div class="section light-bg">

<div class="container">
    <div class="row">
        <div class="col-md-8 d-flex align-items-center">
            <ul class="list-unstyled ui-steps">
                <li class="media">
                    <div class="circle-icon mr-4">1</div>
                    <div class="media-body">
                        <h5>{{ functionalities[0].title }}</h5>
                        <p>{{ functionalities[0].text }} </p>
                    </div>
                </li>
                <li class="media my-4">
                    <div class="circle-icon mr-4">2</div>
                    <div class="media-body">
                        <h5>{{ functionalities[1].title }}</h5>
                        <p>{{ functionalities[1].text }} </p>                    </div>
                </li>
                <li class="media">
                    <div class="circle-icon mr-4">3</div>
                    <div class="media-body">
                        <h5>{{ functionalities[2].title }}</h5>
                        <p>{{ functionalities[2].text }} </p>                    </div>
                </li>
            </ul>
        </div>
        <div class="col-md-4">
            <img :src="functionImage" alt="iphone" class="img-fluid">
        </div>

    </div>

</div>

</div>

</template>

<style scoped></style>