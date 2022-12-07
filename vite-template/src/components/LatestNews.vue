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
            <div class="row justify-content-center">
                <div class="col-10 pb-5">
                    <div class="card py-5 px-1">
                        <div class="title text-center py-3">
                            <h2>Latest News</h2>
                        </div>
                        <div class="card-body text-center ">
                            <div class="container-fluid">
                                <div class="row">
                                    <div class="col-6 p-5">
                                        <img src="../assets/blog-choosecar-700x441.jpg" alt="">
                                        <h4 class="py-2">What Car to Start With?</h4>
                                        <p><small>February 7th 2019 <span>0 comments</span></small></p>
                                        <p>Lorem ipsum dolor sit amet consectetur adipisicing </p>
                                    </div>
                                    <div class="col-6 p-5">
                                        <img src="../assets/blogpost-10and2-700x441.jpg" alt="">
                                        <h4 class="py-2">Avada Driving School Expanding</h4>
                                        <p><small>February 7th 2019 <span>0 comments</span></small></p>
                                        <p>Lorem ipsum dolor sit amet consectetur adipisicing</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <img id="arrow-btm" src="../assets/latestnews-bottom.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    section {
        background-image: url('../assets/latestnews-background.jpg');        
        background-repeat: no-repeat;
        background-size: cover;
        position: relative;
        padding-bottom: 100px;
    }
    .card {
        border-top: 6px solid #7799ad;
        position: relative;
        top: -50px;
        -webkit-box-shadow: 0px 13px 15px 8px rgba(0,0,0,0.68); 
        box-shadow: 0px 13px 15px 8px rgba(0,0,0,0.68);
        border-radius: 15px 15px 0 0;
        border-bottom: 8px solid white;
    }
    h2 {
        font-size: 50px;
    }
    h4, span {
        color: #7abc64;
    }
    p, small {
        color: #ae9aa3;
    }
    img {
        width: 100%;
    }
    #arrow-btm {
        position: absolute;
        bottom: -101px;
        left: 0px;
        width: 100%;
    }
</style>