<script>
import FooterTop from './FooterTop.vue';
import FooterBottom from './FooterBottom.vue';

export default {
    name: 'AppFooter',
    components: {
        FooterTop,
        FooterBottom
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
    <FooterTop/>
    <FooterBottom/>
</template>

<style lang="scss" scoped>

</style>
