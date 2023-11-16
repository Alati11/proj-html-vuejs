<script>


export default {
   
    data() {
        return {
            
            
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
        <ul class="header-link-menu">
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Academics</a></li>
            <li><a href="#">Courses</a></li>
            <li><a href="#">News</a></li>
        </ul>
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
    margin-top: 50px;
    z-index: 50%;
}
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