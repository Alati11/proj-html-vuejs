<script>


export default {


    data() {
        return {


        }
    }
}

</script>

<template>
    <div class="hero">
        <div class="row">
            <div class="hero-title">
                <p class="hero-text">Professional Development For</p>
                <p class="hero-text">Coaches And Leaders</p>
            </div>
            <div>
                <button class="hero-button"> <a href="#">Learn More</a></button>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.hero {
    width: 100%;
    min-height: 600px;
}

.hero-title {
    text-align: center;
    font-size: 55px;
}

.hero-text {
    color: #192836;

}

.row {
    background-image: url('public/img/02_Landing-Page.jpg');
    background-size: cover;
    min-height: 800px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.hero-button {
    border: 1px solid lightgray;
    padding: 15px;
    font-size: 15px;
    width: 165px;
    margin-top: 60px;
    color: gray;
    background-color: transparent;
}

.hero-button:hover {
    color: white;
    background-color: #D74D52;
}
</style>