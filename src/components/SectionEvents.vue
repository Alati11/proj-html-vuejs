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
        <div class="row-eventets ">
            <div class="col">
                <img class="img-events" src="public/img/video-bg-3.jpg" alt="">

                <div class="card-events">
                    <div class="title-events">
                        <h2 class ="title__events-text">Upcoming Events</h2>
                    </div>
                        <p class="events-text">Admission information session and student-led tours to campus visitors</p>
                        <P class="button-more">Learn more ></P>
                        <p class="events-text">Admission information session and student-led tours to campus visitors</p>
                        <P class="button-more">Learn more ></P>
                        <p class="location-text">Event Locations ></p>
                </div>
            </div>
        </div>
    </div>

</template>

<style lang="scss" scoped>
.card-events {
    width: 600px;
    height: 550px;
    margin-left: 260px;
    margin-top: 130px;
    position: absolute;
    background-color: white;
    box-shadow: 5px 5px 5px 5px #dedede;  
    display: flex;
    flex-direction: column;
    justify-content:safe;
    gap: 20px;
    align-items: center;
}

.img-events {
    margin-top: 30px;
    margin-left: -150px;
    min-width: 500px;
}

.col {
    position: relative;
    display: flex;
    
}
.row-eventes {
    justify-content: space-between;
    display: flex;  
}

.title-events {
    color: white;
    background-color:#D74D52;
    width: 320px;
    height: 100px;
    margin-bottom: 55px;
}

.title__events-text {
    text-align: center;
    margin-top: 30px;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
}

.events-text {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 18px;
    padding-left: 40px;
    font-weight: 600;
}

.button-more {
    margin-left: -425px;
    color: #000000;
    font-size: 16px;
    font-weight: 600;
    margin-top: 18px;
}

.location-text {
    margin-top: 30px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    color: #000000;

}

.location-text {
    font-weight: 600;
    font-size: 15px;

}

</style>