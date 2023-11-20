<script setup>
const heading ='Do more with our app';
const subheading='FEATURES';
const datas=[
    {   title:'Communicate with ease',
        subtitle:'Uniquely underwhelm premium outsourcing with proactive leadership skills.',
        description:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer rutrum, urna eu pellentesque pretium, nisi nisi fermentum enim, et sagittis dolor nulla vel sapien. Vestibulum sit amet mattis ante. Ut placerat dui eu nulla congue tincidunt ac a nibh. Mauris accumsan pulvinar lorem placerat volutpat. Praesent quis facilisis elit. Sed condimentum neque quis ex porttitor,',
        src:'/images/graphic.png'
    },
    {
        title:'Scheduling when you want',
        subtitle:'Uniquely underwhelm premium outsourcing with proactive leadership skills.',
        description:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer rutrum, urna eu pellentesque pretium, nisi nisi fermentum enim, et sagittis dolor nulla vel sapien. Vestibulum sit amet mattis ante. Ut placerat dui eu nulla congue tincidunt ac a nibh. Mauris accumsan pulvinar lorem placerat volutpat. Praesent quis facilisis elit. Sed condimentum neque quis ex porttitor,',
        src:'/images/graphic.png'

    },
    {
        title:'Realtime Messaging service',
        subtitle:'Uniquely underwhelm premium outsourcing with proactive leadership skills.',
        description:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer rutrum, urna eu pellentesque pretium, nisi nisi fermentum enim, et sagittis dolor nulla vel sapien. Vestibulum sit amet mattis ante. Ut placerat dui eu nulla congue tincidunt ac a nibh. Mauris accumsan pulvinar lorem placerat volutpat. Praesent quis facilisis elit. Sed condimentum neque quis ex porttitor,',
        src:'/images/graphic.png'

    },
    {
        title:'Live chat when you needed',
        subtitle:'Uniquely underwhelm premium outsourcing with proactive leadership skills.',
        description:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer rutrum, urna eu pellentesque pretium, nisi nisi fermentum enim, et sagittis dolor nulla vel sapien. Vestibulum sit amet mattis ante. Ut placerat dui eu nulla congue tincidunt ac a nibh. Mauris accumsan pulvinar lorem placerat volutpat. Praesent quis facilisis elit. Sed condimentum neque quis ex porttitor,',
        src:'/images/graphic.png'

    },
]
</script>

<template>
    

<div class="section light-bg">
<div class="container">
    <div class="section-title">
        <small>{{subheading}}</small>
        <h3>{{ heading }}</h3>
    </div>

    <ul class="nav nav-tabs nav-justified" role="tablist">
        <li class="nav-item">
            <a class="nav-link active" data-toggle="tab" href="#communication">Communication</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" data-toggle="tab" href="#schedule">Scheduling</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" data-toggle="tab" href="#messages">Messages</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" data-toggle="tab" href="#livechat">Live Chat</a>
        </li>
    </ul>
    <div class="tab-content">
        <div class="tab-pane fade show active" id="communication">
            <div class="d-flex flex-column flex-lg-row">
                <img :src="datas[0].src" alt="graphic" class="img-fluid rounded align-self-start mr-lg-5 mb-5 mb-lg-0">
                <div>
                    <h2>{{ datas[0].title}}</h2>
                    <p class="lead">{{ datas[0].subtitle}}</p>
                    <p>{{ datas[0].description}}</p>
                   
                </div>
            </div>
        </div>
        <div class="tab-pane fade" id="schedule">
            <div class="d-flex flex-column flex-lg-row">
                <div>
                    <h2>{{ datas[1].title}}</h2>
                    <p class="lead">{{ datas[1].subtitle}}</p>
                    <p>{{ datas[1].description}}</p>

                </div>
                <img :src="datas[1].src" alt="graphic" class="img-fluid rounded align-self-start mr-lg-5 mb-5 mb-lg-0">
            </div>
            
        </div>
        <div class="tab-pane fade" id="messages">
            <div class="d-flex flex-column flex-lg-row">
                <img :src="datas[2].src" alt="graphic" class="img-fluid rounded align-self-start mr-lg-5 mb-5 mb-lg-0">
                <div>
                    <h2>{{ datas[2].title}}</h2>
                    <p class="lead">{{ datas[2].subtitle}}</p>
                    <p>{{ datas[2].description}}</p>
                   
                </div>
            </div>
        </div>
        <div class="tab-pane fade" id="livechat">
            <div class="d-flex flex-column flex-lg-row">
                    <div>
                    <h2>{{ datas[3].title}}</h2>
                    <p class="lead">{{ datas[3].subtitle}}</p>
                    <p>{{ datas[3].description}}</p>

                </div>
                <img :src="datas[3].src" alt="graphic" class="img-fluid rounded align-self-start mr-lg-5 mb-5 mb-lg-0">
            </div>
        </div>
    </div>


</div>
</div>
<!-- // end .section -->


</template>
<style scoped>
</style>