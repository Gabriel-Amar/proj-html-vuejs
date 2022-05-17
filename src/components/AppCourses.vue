<template>
    <div class="container">
        <h2 class="text-center fw-bold py-3">
            Recent Courses
        </h2>
        <p class="text-center p-title ">
            Whether you're consideringafoundation course or an undergraduate degree master's
            oraPhD, academics isaplace where students thrive.
        </p>
        <div class="row py-5">
            <div class="col-4">
                <div class="card border-0">
                        <img src="../assets/img/bruce-mars-FWVMhUa_wbY-unsplash.jpg" class="card-img-top  kenburns-top" alt="Online Coaching logo">
                    <div class="card-body">
                        <p>Free</p>
                        <h5 class="card-title">UI Animation using Sketch 3, Principle App, and Flinto</h5>
                        <p class="card-text">This online photography course will teach you how to take amazing images and even sell.</p>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card border-0">
                        <img src="../assets/img/course-1-2.jpg" class="card-img-top  kenburns-top" alt="Online Coaching logo">
                    <div class="card-body">
                        <p>Free</p>
                        <h5 class="card-title">The Ultimate Drawing Course Beginner to Advanced</h5>
                        <p class="card-text">This online photography course will teach you how to take amazing images and even sell.</p>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card border-0">
                        <img src="../assets/img/william-thomas-ny6tO4ItOEY-unsplash.jpg" class="card-img-top  kenburns-top" alt="Online Coaching logo">
                    <div class="card-body">
                        <p>Free</p>
                        <h5 class="card-title">Your Complete Guide to Photography</h5>
                        <p class="card-text">This online photography course will teach you how to take amazing images and even sell.</p>
                    </div>
                </div>
            </div>  
        </div>
        <h2 class="text-center py-5 quote">
            "Academics was committed to my success from the momentIattended an Open House. With the support of caring <span class="colored">advisors, professors, and staff</span>  i was able to thrive in courses, gain recognition through scholarships, and finish <strong>with confidence in my </strong><span class="colored">@academics</span> <strong>abilities.</strong>"
        </h2>
        <div class="row position">
            <div class="col-6 position">
                <img src="../assets/img/video-bg-3.jpg" alt="">
                <i class="fa-regular fa-circle-play"></i>
            </div>
            <div class="col-6 shadow">
                <h2 class="upcoming">Upcoming Events</h2>
                <p class="py-3 margin">Princeton offers admission information sessions and student-led tours to campus visitors</p>
                <p class="py-3">Learn more ></p>
                <p class="py-3">Admission information sessions and student-led tours to campus visitors</p>
                <p class="py-3 margine">Learn more ></p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'AppCourses',
}
</script>

<style scoped lang="scss">
@import "../assets/style/general.scss";
@import "../assets/style/vars.scss";

.quote{
    font-weight: 400;
    background-image: url(../assets/img/quote.png);
    background-repeat: no-repeat;
    background-position: center;
}
.p-title{
    width: $p-width;
    margin: auto;
}
.card{
    box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
}
.card-img-top{
    height: 250px;
}
.colored{
    color: $ac-salmon;
    text-decoration: underline;
    text-decoration-thickness: 1px;
    text-underline-offset: 7px;
}
.upcoming{
    background-color: $ac-salmon;
    color: $ac-white;
    padding: 29px 48px !important;
    margin: auto;
    width: 50%;
    font-size: 27px;
}
.shadow{
    box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
    position: absolute;
    background-color: $ac-white;
    top: 80px;
    right: 150px;
}
.position{
    position: relative;
}
i{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: $ac-white;
    color: $ac-salmon;
    padding: 30px;
    font-size: 40px;
    border-radius: 50%;
}
.margin{
    margin-top: 50px;
}
.margine{
    margin-bottom: 110px;
}
.card:hover .kenburns-top{animation:kenburns-top 1s ease-out both}
@keyframes kenburns-top{0%{transform:scale(1) translateY(0);transform-origin:50% 16%}100%{transform:scale(1.25) translateY(-15px);transform-origin:top}}
</style>

