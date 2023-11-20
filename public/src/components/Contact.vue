<script setup>
const address ='1485 Pacific St, Brooklyn, NY 11216 USA';
const email ='support@mobileapp.com';
const mobile ='518-3636-2800';
const facebook ='#';
const twitter ='#';
const instagram ='#';



</script>
<template>
      <div class="light-bg py-5" id="contact">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 text-center text-lg-left">
                    <p class="mb-2"> <span class="ti-location-pin mr-2"></span> {{ address }}</p>
                    <div class=" d-block d-sm-inline-block">
                        <p class="mb-2">
                            <span class="ti-email mr-2"></span> <a class="mr-4" href="mailto:support@mobileapp.com">{{ email }}</a>
                        </p>
                    </div>
                    <div class="d-block d-sm-inline-block">
                        <p class="mb-0">
                            <span class="ti-headphone-alt mr-2"></span> <a href="tel:51836362800">{{ mobile }}</a>
                        </p>
                    </div>

                </div>
                <div class="col-lg-6">
                    <div class="social-icons">
                        <a :href="facebook"><span class="ti-facebook"></span></a>
                        <a :href="twitter"><span class="ti-twitter-alt"></span></a>
                        <a :href="instagram"><span class="ti-instagram"></span></a>
                    </div>
                </div>
            </div>

        </div>

    </div>

</template>
<style scoped>
</style>