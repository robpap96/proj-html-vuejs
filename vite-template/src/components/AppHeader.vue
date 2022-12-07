<script>
import AppJumbo  from './AppJumbo.vue'

export default {
    name: 'AppHeader',
    components: {
        AppJumbo,
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
    <header>
        <div class="header-top py-3">
            <div class="container">
                <div class="row justify-content-between ">
                    <div class="col-3"><small>We have a 95% rate of Successfull Pass Rate</small></div>
                    <div class="col-4"><small><i class="fa-solid fa-phone"></i> Give us a call to Book your tuition 1-800-555-555</small></div>
                </div>
            </div>
        </div>
        <div class="header-bottom">
            <div class="container">
                <div class="row justify-content-between align-items-center py-5">
                    <div class="col-2">
                        <div class="logo d-flex align-items-center">
                            <img src="../assets/avada-drivers-logo-2x.png" alt="">
                        </div>
                    </div>
                    <div class="col-9 ">
                        <div class="nav-bar">
                            <ul class="d-flex mb-0 align-items-center">
                                <li>HOME</li>
                                <li>ABOUT</li>
                                <li>PRICES</li>
                                <li class="d-flex">COURSERS<span class="badge bg-success ms-2">New</span></li>
                                <li>LOCATION</li>
                                <li>BLOG</li>
                                <li><button class="my-btn ms-3">BOOK NOW</button></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <AppJumbo/>
    </header>
</template>

<style lang="scss" scoped>
header {
    position: sticky;
    z-index: 1000;

    .header-top {
        background-color: #353637;
        color: #929aa3;
    }
    .header-bottom {
        background-color:rgba($color:  #353637, $alpha: 0.4);
        ul{
            list-style: none;
            li{
                color: #ffffff;
                font-weight: bold;
                padding: 0 20px;
            }
            li:hover:not(:last-child) {
                color: #7abc64;
                border-bottom: 2px solid #7abc64;
            }
        }
        .logo {
            img {
                width: 160% ;
            }
        }
    }
    .my-btn {
        background-color:#7abc64;
        border-radius:23px;
        border:2px solid #7abc64;
        display:inline-block;
        cursor:pointer;
        color:#ffffff;
        font-family:Arial;
        font-size:16px;
        padding:10px 20px;
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

}
</style>
