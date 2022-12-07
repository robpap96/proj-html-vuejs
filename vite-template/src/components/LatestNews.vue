<script>
export default {
    name: 'LatestNews',
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
    <section class="latest-news">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="card py-3 px-1">
                    <div class="istructors-image p-3">
                        <img src="../assets/instructor-mikehart-600x381.jpg" alt="">

                    </div>
                    <div class="card-body text-center ">
                        <h5 class="card-title p-2">Mike Hart</h5>
                        <div class="social-links d-flex justify-content-between">
                            <div class="twitter ">
                                <i class="fa-brands fa-twitter"></i>
                            </div>
                            <div class="facebook">
                                <i class="fa-brands fa-facebook-f"></i>
                            </div>
                            <div class="instagram">
                                <i class="fa-brands fa-instagram"></i>
                            </div>
                        </div>
                            <h6 class="card-subtitle text-center py-5 px-3 text-muted">Lorem ipsum dolor sit adj jdhrb dbd asbduh ahnbe absdnf a bssaje.</h6>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script lang="scss" scoped>
    .card {
        border-top: 6px solid #7799ad;

        -webkit-box-shadow: 0px 13px 15px 8px rgba(0,0,0,0.68); 
        box-shadow: 0px 13px 15px 8px rgba(0,0,0,0.68);
    }
</script>