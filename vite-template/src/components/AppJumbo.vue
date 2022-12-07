<script>
//import AppName  from './....AppName.vue'

export default {
    name: 'AppJumbo',
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
    <div class="jumbotron py-5">
        <div class="filter">
            <img src="../assets/homepage-hero-background.jpg" alt="">
        </div>
        <div class="container py-5">
            <div class="row">
                <div class="col-6 py-5">
                    <div class="p-5">
                        <h1>Drive with Avada</h1>
                        <h3>We offer the finest driving tuition money can buy</h3>

                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.jumbotron{
    position: relative;
    img{
        z-index: -1;
        width: 100%;
        position: absolute;
        top: -157px;
        max-height: 800px;
        object-fit: cover;
    }
    .col-6 {
        color: white;
        h1 {
            font-size: 50px;
        }
    }
}
</style>
