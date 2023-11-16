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
        <div>
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
                        <figure class="img-counter1"><span>6500</span></figure>
                        <p class="text-statistics ">Students</p>
                    </div>  
                </div>
                
                <div class="col-3">
                    <div class="card-statistics">
                        <figure class="img-counter1">6500</figure>
                        <p>Students</p>
                    </div>  
                </div>
                <div class="col-3">
                    <div class="card-statistics">
                        <figure class="img-counter1">6500</figure>
                        <p>Students</p>
                    </div>  
                </div>
            </div>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.container-sm {
    width: 800px;
    min-height: 600px;
    margin: 0 auto;
    border-color: 8px solid red;
} 

.student-text {
    font-size: 20px;
    margin-top: 50px;
    margin-left: 20px;
    margin-right: 20px;  
    padding: 40px;
    text-align: center;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-weight: bold;
    color: #192836;
}

.student-text-red {
    color: #FF3A2D;
}

.row {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
}

.col-3 {
    flex-basis: calc((100% / 12) * 3 );
}

.card-students {
    padding: 15px;
    // border: 1px solid lightgray;
    width: 300px;
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
    // margin-top: 30px;
    // width: 300px;
    height: 60px;
    width: 100px;
    aspect-ratio: 1 / 1;
}

.card-statistics {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 300px;
    margin-top:30px;
    padding: 20px;
    gap: 40px;
}

.text-statistics {
    font-size: 20px;
}

</style>