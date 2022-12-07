<script>
export default {
    name: 'YourIstructors',
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
    <div class="container py-5 mt-5">
        <div class="row">
            <div class="col-8">
                <h2 class="p-3">Your Istructors</h2>
                <p class="py-2 px-3">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Minima et vero ducimus tenetur incidunt magni quo. Molestiae et voluptatibus.</p>
            </div>
            <div class="col-4 py-5">
                <button @hover="" type="submit" class="mybtn text-center ">MORE ABOUT US</button>
            </div>
            <div class="col-4">
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
            <div class="col-4">
                <div class="card py-3 px-1">
                    <div class="istructors-image p-3">
                        <img src="../assets/instructor-johnsmith-600x381.jpg" alt="">

                    </div>
                    <div class="card-body text-center">
                        <h5 class="card-title p-2">John Smith</h5>
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
            <div class="col-4">
                <div class="card py-3 px-1">
                    <div class="istructors-image p-3">
                        <img src="../assets/instructor-angelahart-600x381.jpg" alt="">

                    </div>
                    <div class="card-body text-center">
                        <h5 class="card-title p-2">Angela Hart</h5>
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
</template>

<style lang="scss" scoped>
    .card {
        border-top: 6px solid #7abc64;

        -webkit-box-shadow: 0px 13px 15px 8px rgba(0,0,0,0.68); 
        box-shadow: 0px 13px 15px 8px rgba(0,0,0,0.68);
    }
    .mybtn {
    background-color:#7abc64;
    border-radius:23px;
    border:2px solid #7abc64;
    display:inline-block;
    cursor:pointer;
    color:#ffffff;
    font-family:Arial;
    font-size:18px;
    padding:14px 128px;
    margin-top: 50px;
    text-decoration:none;
    text-shadow:0px 0px 2px #2f6627;
    }
    .mybtn:hover {
        background-color:#ffffff;
        color: #7abc64;
    }
    .mybtn:active {
        position:relative;
        top:1px;
    }
    h2 {
        font-size: 50px;
        color: #494c4e;
    }
    p {
        font-size: 25px;
        font-weight: 300;
        line-height: 40px;
        color: #ae9aa3;
    }
    .istructors-image img{
        width: 100%;
    }
    .card-title {
        color: #494c54;
    }
    .card-subtitle {
        color: #bebdbd;
        line-height: 30px;
    }
    .social-links {
        color: #bebdbd;
        width: 20%;
        margin-left: 40%;
    }
</style>