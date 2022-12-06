<script>
import FormSection  from './FormSection.vue'
import StartLearningSection  from './StartLearningSection.vue'
import CoursesSection  from './CoursesSection.vue'
import YourIstructors  from './YourIstructors.vue'

export default {
    name: 'AppMain',
    components: {
        FormSection,
        StartLearningSection,
        CoursesSection,
        YourIstructors,
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
    <YourIstructors/>
</template>

<style lang="scss" scoped>

</style>
