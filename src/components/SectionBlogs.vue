<script>


export default {

    data() {
        return {


        }
    }
}

</script>

<template>
    <div class="container-sm">
        <div class="container-title-courses title-blogs">
            <h2 class="student-text ">Latest From Our Blogs</h2>
            <p class="text-card coursers-text ">Wheter you're considering a foundation
                course or an undergraduate degree master's or a PhD,
                academics is a place where students thrive.
            </p>
        </div>
        <div class="row">
            <div class="col-3">
                <div class="card-courses">
                    <figure>
                        <img class="img-blog" src="public/img/news-3-2.jpg" alt="">
                    </figure>
                    <div class="card-coursers_text">
                        <span>d </span> Admin <span>D </span>University
                        <h3 class="text-blogs">Peer pressure changes how teens tackle inequality</h3>
                        <hr class="line-blogs">
                        <p>Read more ></p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card-courses">
                    <figure>
                        <img class="img-blog" src="public/img/news-2-2.jpg" alt="">
                    </figure>
                    <div class="card-coursers_text">
                        <span><font-awesome-icon :icon="['far', 'user']" /></span> Admin <span>D </span>University
                        <h3 class="text-blogs">Lewisham Live Mixtape celebrates borough's</h3>
                        <hr class="line-blogs">
                        <p>Read more ></p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card-courses">
                    <figure>
                        <img class="img-blog" src="public/img/news-1-2.jpg" alt="">
                    </figure>
                    <div class="card-coursers_text">
                        <span>d </span> Admin <span>D </span>University
                        <h3 class="text-blogs">Turner Prize winner's work to open Gold on film festival</h3>
                        <hr class="line-blogs">
                        <p>Read more ></p>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.title-blogs {
    margin-top: 160px;
}

.text-blogs {
    margin-top: 18px;
    line-height: 1.6em;
    color: #192836;
}

.img-blog {
    width: 500px;
}

.card-coursers_text {
    padding: 22px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}

.line-blogs {
    border: 1px solid #D74D52;
    width: 80px;
    margin-top: 18px;
    margin-bottom: 18px;
}
</style>