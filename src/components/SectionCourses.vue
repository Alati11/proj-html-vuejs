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
        <div class="container-title-courses">
            <h2 class="student-text">Recent Courses</h2>
            <p class="text-card coursers-text">Wheter you're considering a foundation
                course or an undergraduate degree master's or a PhD, 
                academics is a place where students thrive. 
            </p>
        </div>
        <div class="row">
            <div class="col-3">
                <div class="card-courses">
                    <figure>
                        <img src="public/img/bruce-mars-FWVMhUa_wbY-unsplash.jpg" alt="">
                    </figure>
                    <div class="card-coursers_text">
                        <p>Free</p>
                        <h3>Ui Animation using Sketch 3, Principle app, and Flinto</h3>
                        <p>This online photography course will teach you how to take amazing images ans even sell...</p>
                        <p>course by: Univeristy</p>
                    </div>
                    
                </div>
            </div>
            <div class="col-3">
                <div class="card-courses">
                    <figure>
                        <img src="public/img/bruce-mars-FWVMhUa_wbY-unsplash.jpg" alt="">
                    </figure>
                    <p>Free</p>
                    <h3>Ui Animation using Sketch 3, Principle app, and Flinto</h3>
                    <p>This online photography course will teach you how to take amazing images ans even sell...</p>
                    <p>course by: Univeristy</p>
                </div>
            </div>
            <div class="col-3">
                <div class="card-courses">
                    <figure>
                        <img src="public/img/bruce-mars-FWVMhUa_wbY-unsplash.jpg" alt="">
                    </figure>
                    <p>Free</p>
                    <h3 class="courses-title_text">Ui Animation using Sketch 3, Principle app, and Flinto</h3>
                    <p class="courses-subtitle_text">This online photography course will teach you how to take amazing images ans even sell...</p>
                    <p class="courses-sign">course by: Univeristy</p>
                </div>  
            </div>
        </div>
       
    </div>

</template>

<style lang="scss" scoped>   
.coursers-text { 
    margin-left: 50px;
    margin-right: 50px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;  
}
.card-courses {
    width: 350px;
    box-shadow: 5px 5px 5px 5px #dedede;  
    text-align: left;  
    margin-top: 30px; 
}

.card-coursers_text {
    padding: 22px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;

}
</style>