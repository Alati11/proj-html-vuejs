<script>


export default {
    props: ['menu'],
        

    data() {
        return {
        


        }
    }
}

</script>

<template>
    <div>
        <ul class="header-link-menu">
            <li v-for="(link, i) in menu" :key="i">
                <a :href="link.href">{{ link.text }}</a>
            </li>
        </ul>
    </div>
</template>

<style lang="scss" scoped>
.header-link {
    margin-right: 250px;
    font-weight: 600;
}

.header-link-menu {
    display: flex;
    gap: 30px;
}

a:hover {
    color: #FF3A2D;
}
</style>