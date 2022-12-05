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
                    <div class="col-3">
                        <div class="logo">
                            <img src="../assets/avada-drivers-logo-2x.png" alt="">
                        </div>
                    </div>
                    <div class="col-8 ">
                        <div class="nav-bar">
                            <ul class="d-flex mb-0">
                                <li>HOME</li>
                                <li>ABOUT</li>
                                <li>PRICES</li>
                                <li><span>COURSERS</span></li>
                                <li>LOCATION</li>
                                <li>BLOG</li>
                                <li><button class="book-now-btn ms-3">BOOK NOW</button></li>
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
                padding: 0 20px;
            }
        }
        .logo {
            img {
                max-width: 100% ;
            }
        }
    }

}
</style>
