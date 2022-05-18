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
                    <div class="overflow"><img src="../assets/img/bruce-mars-FWVMhUa_wbY-unsplash.jpg" class="card-img-top  kenburns-top" alt="Online Coaching logo">
</div>
                    <div class="card-body">
                        <span class="gradient">Free</span>
                        <h5 class="card-title py-3">UI Animation using Sketch 3, Principle App, and Flinto</h5>
                        <p class="card-text">This online photography course will teach you how to take amazing images and even sell.</p>
                        <p class="card-text color">Course by : University</p>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card border-0">
                    <div class="overflow">
                        <img src="../assets/img/course-1-2.jpg" class="card-img-top  kenburns-top" alt="Online Coaching logo">
                    </div>
                        
                    <div class="card-body">
                        <span class="gradient">Free</span>
                        <h5 class="card-title py-3">The Ultimate Drawing Course Beginner to Advanced</h5>
                        <p class="card-text">This online photography course will teach you how to take amazing images and even sell.</p>
                        <p class="card-text color">Course by : University</p>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card border-0">
                    <div class="overflow">
                        <img src="../assets/img/william-thomas-ny6tO4ItOEY-unsplash.jpg" class="card-img-top  kenburns-top" alt="Online Coaching logo">
                    </div>
                        
                    <div class="card-body">
                        <span class="gradient">Free</span>
                        <h5 class="card-title py-3">Your Complete Guide to Photography for Beginners to Advanced</h5>
                        <p class="card-text">This online photography course will teach you how to take amazing images and even sell.</p>
                        <p class="card-text color">Course by : University</p>
                    </div>
                </div>
            </div>  
        </div>
        <h2 class="text-center quote">
            "Academics was committed to my success from the momentIattended an Open House. With the support of caring <span class="colored">advisors, professors, and staff</span>  i was able to thrive in courses, gain recognition through scholarships, and finish <strong>with confidence in my </strong><span class="colored">@academics</span> <strong>abilities.</strong>"
        </h2>
        <div class="row position">
            <div class="col-6 position">
                <img src="../assets/img/video-bg-3.jpg" alt="">
                <a href="https://player.vimeo.com/external/488076225.hd.mp4?s=9cf4808c4e76c0a9267abb75dbec48bc451a138f&amp;profile_id=175" class="glightbox_video"> 
                <svg width="100" height="100" viewBox="0 0 131 131" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path class="inner-circle" d="M65 21C40.1488 21 20 41.1488 20 66C20 90.8512 40.1488 111 65 111C89.8512 111 110 90.8512 110 66C110 41.1488 89.8512 21 65 21Z" fill="white"></path>
                    <circle class="outer_circle" cx="65.5" cy="65.5" r="64" stroke="white"></circle>
                    <path class="play" fill-rule="evenodd" clip-rule="evenodd" d="M60 76V57L77 66.7774L60 76Z" fill="#BF2428"></path>
                </svg>
                </a>
            </div>
            <div class="col-6 shadow">
                <h2 class="upcoming">Upcoming Events</h2>
                <p class="p-3 margin fw-bold">Princeton offers admission information sessions and student-led tours to campus visitors</p>
                <p class="p-3 hover"><strong>Learn more </strong>></p>
                <p class="p-3 fw-bold">Admission information sessions and student-led tours to campus visitors</p>
                <p class="p-3 margine hover"><strong>Learn more </strong>></p>
                <p class="text-center py-2 hover"><i class="fa-regular fa-map"></i> <strong>Event Locations</strong><span class="rotate-center">></span> </p>
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

.rotate-center:hover {animation:rotate-center .6s ease-in-out both}
@keyframes rotate-center{0%{transform:rotate(0)}100%{transform:rotate(360deg)}}

.hover:hover{
    color: $ac-salmon;
    cursor: pointer;
}
.quote{
    font-weight: 400;
    background-image: url(../assets/img/quote.png);
    background-repeat: no-repeat;
    background-position: center;
    margin-top: 50px;
    margin-bottom: 110px;
}
.p-title{
    width: $p-width;
    margin: auto;
}
.card:hover .card-title{
    color: $ac-salmon;
}
.card{
    box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
    cursor: pointer;
}
.card-img-top{
    height: 208px;
    /* background-size: cover; */
    object-fit: cover;
}
.card-body{
    padding: 30px !important;
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

.margin{
    margin-top: 40px;
}
.margine{
    margin-bottom: 65px;
}
.color{
    color: $ac-salmon;
}
.gradient{
    background: rgb(255,255,255);
background: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(255,255,255,1) 12%, rgba(245,210,212,1) 12%, rgba(255,255,255,1) 50%);
}
.card:hover .kenburns-top{animation:kenburns-top .5s ease-out both}
@keyframes kenburns-top{0%{transform:scale(1) translateY(0);transform-origin:50% 16%}100%{transform:scale(1.25) translateY(-15px);transform-origin:top}}




.glightbox_video {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  }

.outer_circle {
  stroke-width: 3;
  stroke-dasharray: 410; 
   stroke-dashoffset: 0;
  stroke-linecap: square;
  transition: all .4s ease-out;
}

.glightbox_video:hover .outer_circle {
stroke-dashoffset:410;
  transition: stroke .7s .4s ease-out, stroke-dashoffset .4s ease-out
}

.glightbox_video:hover 
.inner-circle {
  fill: $ac-salmon;
  transition:fill .4s .3s ease-out;
  
}

.glightbox_video:hover
.play{
    fill: white;
  transition:fill .4s .3s ease-out;
}
.overflow{
    overflow: hidden;
}
</style>

