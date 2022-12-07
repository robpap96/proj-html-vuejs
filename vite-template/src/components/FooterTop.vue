<script>
export default {
    name: 'FooterTop',
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
    <div class="footer-top p-5">
        <div class="container py-5">
            <div class="row">
                <div class="col-3 px-5">
                    <img src="../assets/avada-drivers-logo-2x.png" alt="">
                    <p>Avada Driving School is the right choice for experienced drivers looking for a refresher course, or the brand new driver wanting to pass first time</p>
                </div>
                <div class="col-3 contact-details px-5 d-flex flex-column">
                    <div class="title py-2">
                        <h3>CONTANCT DETAILS</h3>
                    </div>
                    <div class="footer-item d-flex">
                        <div class="icon">
                            <i class="fa-sharp fa-solid fa-house-chimney"></i>
                        </div>
                        <p>12345 North Main Street, New York, NY 555555</p>

                    </div>
                    <div class="footer-item d-flex">
                        <div class="icon">
                            <i class="fa-solid fa-phone"></i>
                        </div>
                        <p>1.800.555.6789</p>
                         
                    </div>
                    <div class="footer-item d-flex">
                        <div class="icon">
                            <i class="fa-regular fa-envelope"></i>
                        </div>
                        <p>info@your-domain.com</p>
                         
                    </div>
                    <div class="footer-item d-flex">
                        <div class="icon">
                            <i class="fa-solid fa-link"></i>
                        </div>
                        <p>Theme-Fusion.com</p>
                       
                    </div>

                </div>
                <div class="col-3 courses px-5 ">
                    <div class="title py-2">
                        <h3>COURSES</h3>
                    </div>
                    <div class="footer-item d-flex">
                        <div class="circle-arrow">
                           <i class="fa-solid fa-arrow-right"></i> 
                        </div>
                        <p><a href="">Pass Plus</a> </p>
                    </div>
                    <div class="footer-item d-flex">
                        <div class="circle-arrow">
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>
                        <p><a href="">Intensive Course</a> </p>
                         
                    </div>
                    <div class="footer-item d-flex">
                        <div class="circle-arrow">
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>
                        <p><a href="">Automatic</a> </p>
                         
                    </div>
                    <div class="footer-item d-flex">
                        <div class="circle-arrow">
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>
                        <p><a href="">Istructor Training</a> </p>
                         
                    </div>
                </div>
                <div class="col-3 px-5 d-flex justify-content-center flex-wrap">
                    <div class="image">

                        <img src="../assets/Schermata 2022-12-07 alle 23.35.24.png" alt="">
                    </div>

                    <div class="my-btn">BOOK NOW</div>
                </div>
            </div>
        </div>

    </div>

</template>

<style lang="scss" scoped>
    .footer-top {
        background-image: url('../assets/footer-background-color.jpg');
        background-repeat: no-repeat;
        background-size: cover;
    }
    img {
        width: 100%;
        padding-bottom: 20px;
    }
    p, i{
        color: #929ea4;
    }
    i{
        margin-right: 15px;
    }
    .contact-details i{
        color: #929ea4;
    }
    .courses .footer-item i{
        color: #7abc64 ;
    }
    .courses .footer-item p{
        color: #7abc64 ;
    }
    .title h3{
        font-size: 20px;
        color:aliceblue
    }
    a {
        color: inherit;
        text-decoration: none;
    }
    .circle-arrow {
        color: #7abc64;
        width: 25px;
        height: 25px;
        border: solid #7abc64 2px;
        border-radius: 50%;
        padding: 0px 3px;
        margin-right: 8px;
    }
    .my-btn {
        background-color:#7abc64;
        border-radius:23px;
        border:2px solid #7abc64;
        display:inline-block;
        cursor:pointer;
        color:#ffffff;
        font-family:Arial;
        font-size:14px;
        padding:10px 28px;
        text-decoration:none;
        text-shadow:0px 0px 2px #2f6627;
    }
    .my-btn:hover {
        background-color:#ffffff;
        color: #7abc64;
    }
    .my-btn:active {
        position:relative;
        top:1px;
    }
    .image img{
        width: 100%;
    }
</style>