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
    <div class="jumbotron">
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <h1>Drive with Avada</h1>
                    <h3>We offer the finest driving tuition money can buy</h3>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.jumbotron{
    background-image: url('../assets/blogpost-10and2-700x441.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    .col-6 {
        color: white;
    }
}
</style>
