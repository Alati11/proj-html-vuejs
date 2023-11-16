<script>

import AppHero from './AppHero.vue';
import SectionStudents from './SectionStudents.vue';
import SectionCourses from './SectionCourses.vue';


export default {
    components: {
        AppHero,
        SectionStudents,
        SectionCourses,

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
    </div>

</template>

<style lang="scss" scoped>

</style>