<script>
import FormSection  from './FormSection.vue'
import StartLearningSection  from './StartLearningSection.vue'
import CoursesSection  from './CoursesSection.vue'

export default {
    name: 'AppMain',
    components: {
        FormSection,
        StartLearningSection,
        CoursesSection,
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
    <CoursesSection/>
</template>

<style lang="scss" scoped>

</style>
