<template>
    <div class="container">
        <h2 class="text-center fw-bold ">
            Recent Courses
        </h2>
        <p class="text-center p-title py-5">
            Whether you're consideringafoundation course or an undergraduate degree master's
            oraPhD, academics isaplace where students thrive.
        </p>
        <div class="row">
            <div class="col-4">
                <div class="card border-0">
                        <img src="../assets/img/bruce-mars-FWVMhUa_wbY-unsplash.jpg" class="card-img-top " alt="Online Coaching logo">
                    <div class="card-body">
                        <p>Free</p>
                        <h5 class="card-title">UI Animation using Sketch 3, Principle App, and Flinto</h5>
                        <p class="card-text">This online photography course will teach you how to take amazing images and even sell.</p>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card border-0">
                        <img src="../assets/img/course-1-2.jpg" class="card-img-top " alt="Online Coaching logo">
                    <div class="card-body">
                        <p>Free</p>
                        <h5 class="card-title">The Ultimate Drawing Course Beginner to Advanced</h5>
                        <p class="card-text">This online photography course will teach you how to take amazing images and even sell.</p>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card border-0">
                        <img src="../assets/img/william-thomas-ny6tO4ItOEY-unsplash.jpg" class="card-img-top " alt="Online Coaching logo">
                    <div class="card-body">
                        <p>Free</p>
                        <h5 class="card-title">Your Complete Guide to Photography</h5>
                        <p class="card-text">This online photography course will teach you how to take amazing images and even sell.</p>
                    </div>
                </div>
            </div>  
        </div>
        <h2 class="text-center py-5">
            "Academics was committed to my success from the momentIattended an Open House. With the support of caring <span class="colored">advisors, professors, and staff</span>  i was able to thrive in courses, gain recognition through scholarships, and finish <strong>with confidence in my </strong><span class="colored">@academics</span> <strong>abilities.</strong>"
        </h2>
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

h2{
    font-weight: 400;
}
.p-title{
    width: $p-width;
    margin: auto;
}
.card{
    box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
}
img{
    height: 250px;
}
.colored{
    color: $ac-salmon;
    text-decoration: underline;
    text-decoration-thickness: 1px;
    text-underline-offset: 7px;

}
</style>
