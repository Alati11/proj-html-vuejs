<script>

import AppHero from './AppHero.vue';
import SectionStudents from './SectionStudents.vue';
import SectionCourses from './SectionCourses.vue';
import SectionEvents from './SectionEvents.vue'
import SectionBlogs from './SectionBlogs.vue';


export default {
    components: {
        AppHero,
        SectionStudents,
        SectionCourses,
        SectionEvents,
        SectionBlogs,
    },
   
    data() {
        return {
            
            
        }
    }
}

</script>

<template>
    <div>
        <AppHero />
        <SectionStudents />
        <SectionCourses />
        <SectionEvents />
        <SectionBlogs />
    </div>

</template>

<style lang="scss" scoped>

</style>