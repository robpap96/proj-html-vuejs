<script>
import FormSection  from './FormSection.vue'

export default {
    name: 'AppMain',
    components: {
        FormSection,
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
   <FormSection/>
</template>

<style lang="scss" scoped>

</style>
