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
        <div class="container-text">
            <p class="student-text">Since 2000, weve been partnering with education leaders to
                <span class="student-text-red">incrause equity and achievement </span>for all student.
            </p>
        </div>
        
        <div class="row">
            <div class="col-3">
                <div class="card-students">
                    <img class="card-students-img" src="public/svg/svg-0.svg" alt="">
                    <h3 class="title-card"><a href="#">Online Coaching</a></h3>
                    <p class="text-card">Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
                        Quisquam sit quibusdam totam quis consequatur voluptas!</p>
                </div>
            </div>
            <div class="col-3">
                <div class="card-students">
                    <img class="card-students-img" src="public/svg/svg-1.svg" alt=""> 
                    <h3 class="title-card"><a href="#">Consultation</a></h3>
                    <p class="text-card">Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
                        Quisquam sit quibusdam totam quis consequatur voluptas!</p>
                </div>
            </div>
            <div class="col-3">
                <div class="card-students">
                    <img class="card-students-img" src="public/svg/svg-2.svg" alt="">
                    <h3 class="title-card"> <a href="#">Life Programs</a></h3>
                    <p class="text-card">Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
                        Quisquam sit quibusdam totam quis consequatur voluptas!</p>
                </div>            
            </div>
        </div> 

        <div class="container-sm">
            <div class="row">
                <div class="col-3">
                    <div class="card-statistics">
                        <figure class="img-counter1"><span class="counter bg-org">6500 +</span></figure>
                        <p class="text-statistics">Students</p>
                    </div>  
                </div>
                
                <div class="col-3">
                    <div class="card-statistics">
                        <figure class="img-counter2"><span class="counter bg-red">200 +</span></figure>
                        <p class="text-statistics">Online courses</p>
                    </div>  
                </div>
                <div class="col-3">
                    <div class="card-statistics">
                        <figure class="img-counter3"><span class="counter bg-green">100 %</span></figure>
                        <p class="text-statistics">Happy Clients</p>
                    </div>  
                </div>
            </div>
        </div>
    </div>

</template>

<style lang="scss" scoped>


.student-text {
    width: 100%;
    font-size: 26px;
    text-align: center;
    line-height: 1.8em;
    margin-top: 50px;
    margin-left: 20px;
    margin-right: 20px;  
    padding: 20px;
    text-align: center;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-weight: bold;
    color: #192836;
}

.student-text-red {
    color: #FF3A2D;
}

.card-students {
    padding: 15px;
    width: 350px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    box-shadow: 5px 5px 5px 5px #dedede; 
}

.title-card {
    font-size: 18px;
    padding: 18px;
    text-align: center;
    color: #192836  ;
}

.text-card {
    line-height: 1.8em;
    font-size: 15px;
    text-align: center;
    margin-bottom: 20px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}

.card-students-img {
    height: 60px;
}

a:hover {
    color: #FF3A2D;
}
.img-counter1 {
    background-image: url('public/img/counter-shape-1-1-1.png');
    background-repeat: no-repeat;
    height: 69px;
    width: 88px;
    aspect-ratio: 1 / 1;
}

.img-counter2 {
    background-image: url('public/img/counter-shape-2-1-1.png');
    background-repeat: no-repeat;
    height: 69px;
    width: 88px;
    aspect-ratio: 1 / 1;
}

.img-counter3 {
    background-image: url('public/img/counter-shape-3-1-1.png');
    background-repeat: no-repeat;
    height: 69px;
    width: 88px;
    aspect-ratio: 1 / 1;
}


.card-statistics {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 350px;
    margin-top:30px;
    padding: 20px;
    gap: 40px;
}

.text-statistics {
    font-size: 16px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}

.counter{
    font-weight:800;
    height: 10px;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-size: 35px;
    text-align: center;
    position:absolute;
    margin-top: 10px;
    margin-left: -20px;
    
}
.bg-org {
    color: #F28202;
}

.bg-red {
    color: #D74D52;
}
.bg-green {
    color:#3ADC79;
}

.container-text {
    display: flex;
    justify-content: center;
    width: 800px;
}
</style>