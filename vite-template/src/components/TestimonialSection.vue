<script>
export default {
    name: 'TestimonialSection',
    components: {

    },
    defineProps :{
        //msg: String
    },
    data(){
        return {
            //
        }
    },


}
</script>

<template>
    <section class="testimonial-section pb-5">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-8 py-5 mt-5">
                    <div class="section-title text-center">
                        <h2>Testimonials</h2>
                        <p>Here's what our happy drivers had to say about our service:</p>

                    </div>
                    <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
                        <div class="carousel-indicators">
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 4"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="4" aria-label="Slide 5"></button>
                        </div>
                        <div class="carousel-inner">
                            <div class="carousel-item active" data-bs-interval="3000">
                                <img src="../assets/testimonial-grant.png" class="d-block " alt="testimonial-grant">
                                <div class="carousel-caption d-none d-md-block">
                                    <p class="p-3">Avada Driver really helped build my confidence behind the wheel and with driving in general, and they got me a first time pass! Highly recommended.</p>
                                    <h5 class="p-3">Grant Harrison</h5>
                                </div>
                            </div>
                            <div class="carousel-item" data-bs-interval="3000">
                                <img src="../assets/testimonial-harold.png" class="d-block " alt="testimonial-harold">
                                <div class="carousel-caption d-none d-md-block">
                                    <p class="p-3">Avada Driver really helped build my confidence behind the wheel and with driving in general, and they got me a first time pass! Highly recommended.</p>
                                    <h5 class="p-3">Harold Davids</h5>
                                </div>
                            </div>
                            <div class="carousel-item" data-bs-interval="3000">
                                <img src="../assets/testimonial-kate.png" class="d-block " alt="testimonial-kate">
                                <div class="carousel-caption d-none d-md-block">
                                    <p class="p-3">Avada Driver really helped build my confidence behind the wheel and with driving in general, and they got me a first time pass! Highly recommended.</p>
                                    <h5 class="p-3">Kate Callister</h5>
                                </div>
                            </div>
                            <div class="carousel-item" data-bs-interval="3000">
                                <img src="../assets/testimonial-kelly.png" class="d-block " alt="testimonial-kelly">
                                <div class="carousel-caption d-none d-md-block">
                                    <p class="p-3">Avada Driver really helped build my confidence behind the wheel and with driving in general, and they got me a first time pass! Highly recommended.</p>
                                    <h5 class="p-3">Kelly Smith</h5>
                                </div>
                            </div>
                            <div class="carousel-item" data-bs-interval="3000">
                                <img src="../assets/testimonial-sophia.png" class="d-block " alt="testimonial-sophia">
                                <div class="carousel-caption d-none d-md-block">
                                    <p class="p-3">Avada Driver really helped build my confidence behind the wheel and with driving in general, and they got me a first time pass! Highly recommended.</p>
                                    <h5 class="p-3">Sophia Johnson</h5>
                                </div>
                            </div>
                        </div>

                    </div>

                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    .testimonial-section{
        background-image: url('../assets/testimonial-background.jpg');
        background-repeat: no-repeat;
        background-size: cover;
    }
    .carousel-item img {
        margin-top: 150px;
        width: 22%;
        margin-bottom: 300px;
        margin-left: 344px;
    }
    h2 {
        font-size: 50px;
    }
    h5, p {
        color: #929aa3;
        line-height: 40px;
    }
    p {
        font-style: italic;
        font-weight: 300;
        font-size: 20px;
    }
    .carousel-indicators > *{
        width: 10px !important;
        height: 10px !important;
        border-radius: 50%;
    }
    .carousel-indicators > .active {
        color: #929aa3 !important;

    }
</style>