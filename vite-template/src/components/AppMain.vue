<script>
import FormSection  from './FormSection.vue'
import StartLearningSection  from './StartLearningSection.vue'
import CoursesSection  from './CoursesSection.vue'
import YourIstructors  from './YourIstructors.vue'
import TestimonialSection  from './TestimonialSection.vue'
import LatestNews  from './LatestNews.vue'
import NewsletterSection  from './NewsletterSection.vue'

export default {
    name: 'AppMain',
    components: {
        FormSection,
        StartLearningSection,
        CoursesSection,
        YourIstructors,
        TestimonialSection,
        LatestNews,
        NewsletterSection,
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
    <TestimonialSection/>
    <LatestNews/>
    <NewsletterSection/>
</template>

<style lang="scss" scoped>

</style>
