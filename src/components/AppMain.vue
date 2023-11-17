<script>

import AppHero from './AppHero.vue';
import SectionStudents from './SectionStudents.vue';
import SectionCourses from './SectionCourses.vue';
import SectionEvents from './SectionEvents.vue'


export default {
    components: {
        AppHero,
        SectionStudents,
        SectionCourses,
        SectionEvents,

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
    </div>

</template>

<style lang="scss" scoped>

</style>