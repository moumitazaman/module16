<script setup>
const heading ='Do more with our app';
const subheading='TESTIMONIALS';
const datas=[
    
    {
        clientName:'Crystal Gordon',
        location:'United States',
        comment:'Uniquely streamline highly efficient scenarios and 24/7 initiatives. Conveniently embrace multifunctional ideas through proactive customer service. Distinctively conceptualize 2.0 intellectual capital via user-centric partnerships',
        src:'/images/client.png'

    },
    {
        clientName:'Emily Richards',
        location:'United States',
        comment:'Uniquely streamline highly efficient scenarios and 24/7 initiatives. Conveniently embrace multifunctional ideas through proactive customer service. Distinctively conceptualize 2.0 intellectual capital via user-centric partnerships',
        src:'/images/client.png'

    },
    {
        clientName:'Jane Doe',
        location:'United States',
        comment:'Uniquely streamline highly efficient scenarios and 24/7 initiatives. Conveniently embrace multifunctional ideas through proactive customer service. Distinctively conceptualize 2.0 intellectual capital via user-centric partnerships',
        src:'/images/client.png'

    },
]
</script>
<template>
    
    <div class="section">
        <div class="container">
            <div class="section-title">
                <small>{{ subheading }}</small>
                <h3>{{ heading }}</h3>
            </div>

            <div class="testimonials owl-carousel">
                <div class="testimonials-single">
                    <img :src="datas[0].src" alt="client" class="client-img">
                    <blockquote class="blockquote">{{ datas[0].comment }}</blockquote>
                    <h5 class="mt-4 mb-2">{{ datas[0].clientName }}</h5>
                    <p class="text-primary">{{ datas[0].location }}</p>
                </div>
                <div class="testimonials-single">
                    <img :src="datas[1].src" alt="client" class="client-img">
                    <blockquote class="blockquote">{{ datas[1].comment }}</blockquote>
                    <h5 class="mt-4 mb-2">{{ datas[1].clientName }}</h5>
                    <p class="text-primary">{{ datas[1].location }}</p>
                </div>
                <div class="testimonials-single">
                    <img :src="datas[2].src" alt="client" class="client-img">
                    <blockquote class="blockquote">{{ datas[2].comment }}</blockquote>
                    <h5 class="mt-4 mb-2">{{ datas[2].clientName }}</h5>
                    <p class="text-primary">{{ datas[2].location }}</p>
                </div>
            </div>

        </div>

    </div>

</template>
<style scoped></style>