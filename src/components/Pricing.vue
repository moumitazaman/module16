<script setup>
const heading ='Upgrade to Pro';
const subheading='Pricing';
const datas=[
    
    {
        planName:'Personal',
        price:'$14',
        features:["10 Projects","5 GB Storage","Basic Support","Collaboration","Reports Analytics"],
        link:'#'

    },
    {
        planName:'For Teams',
        price:'$29',
        features:["Unlimited Projects","100 GB Storage","Priority Support","Collaboration","Reports Analytics"],
        link:'#'

    },
    {
        planName:'Enterprise',
        price:'$249',
        features:["Unlimited Projects","Unlimited Storage","Collaboration","Reports Analytics","Web Hooks"],
        link:'#'

    },
]
</script>
<template>
    <div class="section" id="pricing">
        <div class="container">
            <div class="section-title">
                <small>{{subheading}}</small>
                <h3>{{heading}}</h3>
            </div>

            <div class="card-deck">
                <div class="card pricing">
                    <div class="card-head">
                        <small class="text-primary">{{datas[0].planName}}</small>
                        <span class="price">{{ datas[0].price }}<sub>/m</sub></span>
                    </div>
                    <ul class="list-group list-group-flush">
                        <div class="list-group-item">{{ datas[0].features[0] }}</div>
                        <div class="list-group-item">{{ datas[0].features[1] }}</div>
                        <div class="list-group-item">{{ datas[0].features[2] }}</div>
                        <div class="list-group-item"><del>{{ datas[0].features[3] }}</del></div>
                        <div class="list-group-item"><del>{{ datas[0].features[4] }}</del></div>
                    </ul>
                    <div class="card-body">
                        <a :href="datas[0].link" class="btn btn-primary btn-lg btn-block">Choose this Plan</a>
                    </div>
                </div>
                <div class="card pricing popular">
                    <div class="card-head">
                        <small class="text-primary">{{datas[1].planName}}</small>
                        <span class="price">{{ datas[1].price }}<sub>/m</sub></span>
                    </div>
                    <ul class="list-group list-group-flush">
                        <div class="list-group-item">{{ datas[1].features[0] }}</div>
                        <div class="list-group-item">{{ datas[1].features[1] }}</div>
                        <div class="list-group-item">{{ datas[1].features[2] }}</div>
                        <div class="list-group-item">{{ datas[1].features[3] }}</div>
                        <div class="list-group-item">{{ datas[1].features[4] }}</div>
                    </ul>
                    <div class="card-body">
                        <a :href="datas[1].link" class="btn btn-primary btn-lg btn-block">Choose this Plan</a>
                    </div>
                 
                </div>
                <div class="card pricing">
                    <div class="card-head">
                        <small class="text-primary">{{datas[2].planName}}</small>
                        <span class="price">{{ datas[2].price }}<sub>/m</sub></span>
                    </div>
                    <ul class="list-group list-group-flush">
                        <div class="list-group-item">{{ datas[2].features[0] }}</div>
                        <div class="list-group-item">{{ datas[2].features[1] }}</div>
                        <div class="list-group-item">{{ datas[2].features[2] }}</div>
                        <div class="list-group-item">{{ datas[2].features[3] }}</div>
                        <div class="list-group-item">{{ datas[2].features[4] }}</div>
                    </ul>
                    <div class="card-body">
                        <a :href="datas[2].link" class="btn btn-primary btn-lg btn-block">Choose this Plan</a>
                    </div>
                   
                </div>
            </div>
            <!-- // end .pricing -->


        </div>

    </div>

</template>
<style scoped>
</style>