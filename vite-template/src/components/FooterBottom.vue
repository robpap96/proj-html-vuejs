<script>
export default {
    name: 'FooterBottom',
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
    <div class="footer-bottom p-5" style="background-color: #1c1d1e;">
        <div class="container py-1">
            <div class="row justify-content-between">
                <div class="col-7">
                    <div class="copyright">
                        <small><i class="fa-regular fa-copyright"></i>Copyright 2012 - 2020 | Avada Theme by <a href="">ThemeFusion</a> | All Rights Reserved | Powered by <a href="">WordPress</a> </small>
                    </div>
                </div>
                <div class="col-2">
                    <div class="social d-flex justify-content-around">
                        <div class="facebook"><i class="fa-brands fa-facebook-f"></i></div>
                        <div class="twitter"><i class="fa-brands fa-twitter"></i></div>
                        <div class="youtube"><i class="fa-brands fa-youtube"></i></div>
                        <div class="instagram"><i class="fa-brands fa-instagram"></i></div>
                    </div>
                </div>
            </div>
        </div>

    </div>

</template>

<style lang="scss" scoped>

    .copyright small{
        color: #6a6c71;
    }
    .copyright a {
        text-decoration: none;
        color: #7abc64;
    }
    i {
        color: #ffffff;
    }
</style>