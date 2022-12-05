<script>
export default {
    name: 'FormSection',
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
    <div class="section py-5" style="margin-top: 100px">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-6">
                    <h2 class="py-4">Get Behind The Wheel</h2>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Animi maxime saepe repudiandae nulla obcaecati aliquam quia iusto exercitationem accusantium corrupti officiis commodi qui provident, ex deserunt nesciunt error eos cum.</p>
                    <p><small>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quisquam suscipit voluptatem, deserunt maxime fuga voluptatum qui ad velit sunt quis exercitationem optio animi ipsa corrupti obcaecati quam eum, accusamus ut? Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci illum eligendi natus aspernatur quibusdam, inventore laborum animi molestias vero similique at numquam sapiente iusto aperiam est velit rerum quidem repudiandae.</small></p>
                    
                </div>
                <div class="col-6">
                    <div class="card p-3">
                        <div class="card-body text-center">
                            <h5 class="card-title p-4">First Lesson Free!</h5>
                            <h6 class="card-subtitle text-center p-5 mb-2 text-muted">When you make a black booking with us your first lesson is included free.</h6>
                            <form>
                            <div class="mb-5">
                                <input type="text" class="form-control py-3" id="" aria-describedby="textHelp" placeholder="Your Name*" required>
                            </div>
                            <div class="mb-5">
                                <input type="email" class="form-control py-3" id="" aria-describedby="emailHelp" placeholder="Email*" required>
                            </div>
                            <div class="mb-5">
                                <input type="text" class="form-control py-3" id="" placeholder="Telephone">
                            </div>
                            <div class="mb-5">
                                <input type="text" class="form-control py-3" id="" placeholder="Location">
                            </div>
                            <button type="submit" class="mybtn text-center">REQUEST A CALLBACK</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .card {
        position: relative;
        top: -70px;
        z-index: 1000;
        -webkit-box-shadow: 0px 13px 15px 8px rgba(0,0,0,0.68); 
        box-shadow: 0px 13px 15px 8px rgba(0,0,0,0.68);
    }
    .col-6 {
        h2 {
            font-size: 38px;
        }
    }
    p{       
        font-size: 23px;  
        font-weight: lighter;
        color: #999aa3;
        small {
            font-size: 18px;
        }
    }
    .card-title{
        color: #7abc64;
        font-size: 35px;
        .card-subtitle {
            font-size: 28px;
        }
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
        padding:14px 48px;
        text-decoration:none;
        text-shadow:0px 0px 2px #2f6627;
    }
    .mybtn:hover {
        background-color:#ffffff;
        color: #7abc64;
    }
    // .mybtn:active {
    //     position:relative;
    //     top:1px;
    // }

        
    
</style>