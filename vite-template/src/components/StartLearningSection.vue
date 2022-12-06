<script>
export default {
    name: 'StartLearningSection',
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
    <section>
        <div class="container">
            <div class="row justify-content-between py-5">
                <div class="col-6 py-3">
                    <h2>Start Learning to Drive Today</h2>
                    <h4>Give us a call to schedule your first driving section</h4>
                </div>
                <div class="col-3 py-5">
                    <h3><i class="fa-solid fa-phone"></i> 1-800-555-555</h3>
                </div>
            </div>
        </div>

    </section>
</template>

<style lang="scss" scoped>
section {
    background-image: url('../assets/horizontal-cta-background.jpg');
    background-size: cover;
    .col-6, .col-3 {
        color: white;
    }
}
</style>