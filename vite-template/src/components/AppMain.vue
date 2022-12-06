<script>
import FormSection  from './FormSection.vue'
import StartLearningSection  from './StartLearningSection.vue'

export default {
    name: 'AppMain',
    components: {
        FormSection,
        StartLearningSection,
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
   <StartLearningSection/>
</template>

<style lang="scss" scoped>

</style>
