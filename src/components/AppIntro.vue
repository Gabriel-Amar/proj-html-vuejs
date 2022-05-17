<template>
    <div class="container">
        <h2 class="text-center my-5 fw-bold">
            Since 2000, wave been partnering with education leaders to <span class="colored">increase equity and achievement</span>  for all students.
        </h2>
        <div class="row">
            <div class="col-4">
                <div class="card border-0 p-5 slide-top">
                        <img src="../assets/img/svg-0.svg" class="card-img-top" alt="Online Coaching logo">
                    <div class="card-body text-center">
                        <h5 class="card-title">Online Coaching</h5>
                        <p class="card-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quas corporis odio veritatis tempora. Libero, alias velit?</p>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card border-0 p-5 slide-top">
                        <img src="../assets/img/svg-1.svg" class="card-img-top" alt="Online Coaching logo">
                    <div class="card-body text-center">
                        <h5 class="card-title">Consultation</h5>
                        <p class="card-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quas corporis odio veritatis tempora. Libero, alias velit?</p>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card border-0 p-5 slide-top">
                        <img src="../assets/img/svg-2.svg" class="card-img-top" alt="Online Coaching logo">
                    <div class="card-body text-center">
                        <h5 class="card-title">Life Programs</h5>
                        <p class="card-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quas corporis odio veritatis tempora. Libero, alias velit?</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="row my-5">
            <div class="col-4 text-center d-flex justify-content-center align-items-center">
                <span class="students">
                    6500 + 
                </span>
                <span class="text">
                    Students
                </span>
            </div>
            <div class="col-4 text-center  d-flex justify-content-center align-items-center">
                <span class="courses">
                    200 + 
                </span>
                <span class="text">
                    Online Courses
                </span>
            </div>
            <div class="col-4 text-center  d-flex justify-content-center align-items-center">
                <span class="happy">
                    99 %
                </span>
                <span class="text">
                    Happy Clients
                </span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AppIntro',
}
</script>

<style scoped lang="scss">
@import "../assets/style/general.scss";
@import "../assets/style/vars.scss";

h2{
    width: $title-width;
    margin: auto;
}
img{
    width: 60px !important;
    margin: auto;
}
.card{
    box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
}
.colored{
    color: $ac-salmon;
}
.students{
    color: $ac-orange;
    background-image: url(../assets/img/counter-shape-1-1-1.png);
}
.courses{
    color: $ac-salmon;
        background-image: url(../assets/img/counter-shape-2-1-1.png);
}
.happy{
    color: $ac-green;
        background-image: url(../assets/img/counter-shape-3-1-1.png);
}
.students, .courses, .happy{
    font-weight: 700;
    font-size: $num-size;
    font-family: $num-family;
    background-repeat: no-repeat;
    background-size: contain;
    cursor: default;
}
.students{
        background-position: 16px;
}
.text{
    font-weight: 500;
}
.colored:hover{
    text-decoration: underline;
    cursor: pointer;
}
.slide-top:hover{animation:slide-top .5s cubic-bezier(.25,.46,.45,.94) both}
@keyframes slide-top{0%{transform:translateY(0)}100%{transform:translateY(-20px)}}

.card:hover .card-title{
    color: $ac-salmon;
} 

</style>


