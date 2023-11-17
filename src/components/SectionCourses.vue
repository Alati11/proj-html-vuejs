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
                        <p class="free-text">Free</p>
                        <h3 class="courses-title__text">Ui Animation using Sketch 3, Principle app, and Flinto</h3>
                        <p class="text__sub">This online photography course will teach you how to take amazing images ans even sell...</p>
                        <p class="courses-sign">Course by: Univeristy</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card-courses">
                    <figure>
                        <img class="img-pc" src="public/img/course-1-2.jpg" alt="">
                    </figure>
                    <div class="card-coursers_text">
                        <p class="free-text">Free</p>
                        <h3 class="courses-title__text">The Ultimate Drawing Course - Beginner to Advanced</h3>
                        <p class="text__sub">This online photography course will teach you how to take amazing images ans even sell...</p>
                        <p class="courses-sign">Course by: Univeristy</p>
                    </div>
                </div>
            </div>

            <div class="col-3">
                <div class="card-courses">
                    <figure>
                        <img src="public/img/william-thomas-ny6tO4ItOEY-unsplash.jpg" alt="">
                    </figure>
                    <div class="card-coursers_text">
                        <p class="free-text">Free</p>
                        <h3 class="courses-title__text">Ui Animation using Sketch 3, Principle app, and Flinto</h3>
                        <p class="text__sub">This online photography course will teach you how to take amazing images ans even sell...</p>
                        <p class="courses-sign">Course by: Univeristy</p>
                    </div>
                </div>
            </div>
        </div>
    </div> 

    <div class="container-sm">
        <div class="row">
            <div class="col">
                <div class="bg-courses">
                    <p class="courses-info ">"Academics was commited to my success from the moment
                        I attended an Open House. With the support pf caring 
                        <span class="under-red">advisors, professors, and staff</span>
                         i was aable to thrive in courses, again recognition trough
                        scholarships, and finish 
                        <span class="text-bold">with confidence in my </span>
                        <span class="under-red">@academics</span>
                        <span class="text-bold"> abilities"</span>
                    </p>
                </div>
            </div>
        </div>
    </div>    
       
</template>

<style lang="scss" scoped>   
.coursers-text { 
    margin-left: 50px;
    margin-right: 50px;
    font-size: 22px;
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
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}

.courses-title__text {
    margin-top: 15px;
    line-height: 1.6em;
    font-weight:00;
    font-size: 22px;
}

.text__sub {
    line-height: 1.8em;
    margin-top: 20px;
    font-size: 19px;
}

.courses-sign {
    font-size: 13px;
    color: #FF3A2D;
    margin-top: 20px;
}

.img-pc {
    height: 235px;
}

.free-text {
    border-bottom: 2px solid #D74D5240;
    width: 32px;
    border-width: 10px; 
}

.bg-courses {
    background-image: url('public/img/quote.png');
    background-repeat: no-repeat;
    margin-top: 60px;
    margin-left: 650px
}

.courses-info  {
  font-size: 26px;
  margin-left: -600px;
  margin-right: 20px;  
  padding: 40px;
  line-height: 1.8em;
  text-align: center;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  color: #192836;
  width: 1100px;
}

.under-red {
    color: #D74D52;
    text-decoration: underline;
    font-weight: 600;
}
 .text-bold {
    font-weight: 600;
 }
</style>