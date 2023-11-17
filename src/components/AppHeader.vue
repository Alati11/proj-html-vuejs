<script>

import AppHeaderMenu from './AppHeaderMenu.vue'


export default {
    components: {
        AppHeaderMenu,
    },

    data() {
        return {
            menu: [
                {
                    text: 'Home',
                    href: '#',
                },
                {
                    text: 'About',
                    href: '#',
                },
                {
                    text: 'Academics',
                    href: '#',
                },
                {
                    text: 'Courses',
                    href: '#',
                },
                {
                    text: 'News',
                    href: '#',
                },
            ]

        }
    }
}

</script>

<template>
    <div class="header-container">
        <div class="header-img">
            <img class="header-logo" src="public/img/Logo.jpg" alt="">
        </div>
        <div class="header-link">
            <AppHeaderMenu :menu="menu"/>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.header-container {
    height: 80px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.header-img {
    margin-left: 250px;
}

.header-logo {
    height: 120px;
    margin-top: 40px;
    z-index: 50%;
}

.header-link {
    margin-right: 250px;
    font-weight: 600;
}

</style>