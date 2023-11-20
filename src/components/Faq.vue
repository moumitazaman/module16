<script setup>
const heading ='FAQ'; 
const subheading='Frequently Asked Questions';

const datas= [
    {
        title:'Can I try before I buy?',
        text:'Lorem ipsum dolor sit amet',

    },
    {
        title:'What payment methods do you accept?',
        text:'Lorem ipsum dolor sit amet',

    },
    {
        title:'Can I change my plan later?',
        text:'Lorem ipsum dolor sit amet',

    }
    ,
    {
        title:'Do you have a contract?',
        text:'Lorem ipsum dolor sit amet',

    }
    


]

</script>
<template>
        <div class="section pt-0">
        <div class="container">
            <div class="section-title">
                <small>{{ subheading }}</small>
                <h3>{{ heading }}</h3>
            </div>

            <div class="row pt-4">
                <div class="col-md-6">
                    <h4 class="mb-3">{{ datas[0].title }}</h4>
                    <p class="light-font mb-5">{{ datas[0].text }}</p>
                    <h4 class="mb-3">{{ datas[1].title }}</h4>
                    <p class="light-font mb-5">{{ datas[1].text }}</p>

                </div>
                <div class="col-md-6">
                    <h4 class="mb-3">{{ datas[2].title }}</h4>
                    <p class="light-font mb-5">{{ datas[2].text }}</p>

                    <h4 class="mb-3">{{ datas[3].title }}</h4>
                    <p class="light-font mb-5">{{ datas[3].text }}</p>

                </div>
            </div>
        </div>

    </div>

</template>
<style scoped>
</style>