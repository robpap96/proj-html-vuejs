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
                    <div class="istructors-image p-5">
                        <img src="../assets/instructor-mikehart-600x381.jpg" alt="">

                    </div>
                    <div class="card-body text-center">
                        <h5 class="card-title p-2">Courses</h5>
                        <h6 class="card-subtitle text-center py-5 px-3 text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel voluptates omnis voluptatem asperiores, reprehenderit autem quam repellat illo accusantium reiciendis veniam corrupti alias nulla officiis! Iusto sint tenetur deserunt odit.</h6>
                        <button @hover="" type="submit" class="mybtn text-center">COURSE INFORMATION</button>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card py-3 px-1">
                    <div class="istructors-image p-5">
                        <img src="../assets/instructor-johnsmith-600x381.jpg" alt="">

                    </div>
                    <div class="card-body text-center">
                        <h5 class="card-title p-2">Courses</h5>
                        <h6 class="card-subtitle text-center py-5 px-3 text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel voluptates omnis voluptatem asperiores, reprehenderit autem quam repellat illo accusantium reiciendis veniam corrupti alias nulla officiis! Iusto sint tenetur deserunt odit.</h6>
                        <button @hover="" type="submit" class="mybtn text-center">COURSE INFORMATION</button>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card py-3 px-1">
                    <div class="istructors-image p-5">
                        <img src="../assets/instructor-angelahart-600x381.jpg" alt="">

                    </div>
                    <div class="card-body text-center">
                        <h5 class="card-title p-2">Courses</h5>
                        <h6 class="card-subtitle text-center py-5 px-3 text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel voluptates omnis voluptatem asperiores, reprehenderit autem quam repellat illo accusantium reiciendis veniam corrupti alias nulla officiis! Iusto sint tenetur deserunt odit.</h6>
                        <button @hover="" type="submit" class="mybtn text-center">COURSE INFORMATION</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
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
</style>