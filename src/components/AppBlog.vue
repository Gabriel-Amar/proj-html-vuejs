<template>
    <div class="container">
        <h2 class="text-center fw-bold title py-5">
            Latest From Our Blog
        </h2>
        <p class="text-center p-title  w-50 m-auto">
            Whether you're consideringafoundation course or an undergraduate degree master's
            oraPhD, academics isaplace where students thrive.
        </p>
        <div class="row py-5">
            <div class="col-4">
                <div class="card border-0">
                    <div class="overflow">
                        <img src="../assets/img/news-3-2.jpg" class="card-img-top kenburns-top" alt="...">
                    </div>
                    
                    <div class="card-body">
                        <p class="card-text d-flex align-items-center gap-2 py-1"><i class="fa-regular fa-user"></i>Admin<i class="fa-regular fa-folder"></i>University</p>
                        <h5 class="card-title">Peer pressure changes how teens tackle inequality</h5>
                        <div class="border border-danger"></div>
                        <p class="card-text">Read more ></p>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card border-0">
                    <div class="overflow">
                        <img src="../assets/img/news-3-2.jpg" class="card-img-top kenburns-top" alt="...">
                    </div>
                    <div class="card-body">
                        <p class="card-text d-flex align-items-center gap-2 py-1"><i class="fa-regular fa-user"></i>Admin<i class="fa-regular fa-folder"></i>Education</p>
                        <h5 class="card-title">Peer pressure changes how teens tackle inequality</h5>
                        <div class="border border-danger"></div>
                        <p class="card-text">Read more ></p>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card border-0">
                    <div class="overflow">
                        <img src="../assets/img/news-3-2.jpg" class="card-img-top kenburns-top" alt="...">
                    </div>
                    <div class="card-body">
                        <p class="card-text d-flex align-items-center gap-2 py-1"><i class="fa-regular fa-user"></i>Admin<i class="fa-regular fa-folder"></i>University</p>
                        <h5 class="card-title">Peer pressure changes how teens tackle inequality</h5>
                        <div class="border border-danger"></div>
                        <p class="card-text">Read more ></p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'AppBlog',
}
</script>

<style scoped lang="scss">
@import "../assets/style/general.scss";
@import "../assets/style/vars.scss";

.card:hover .card-title{
    color: $ac-salmon;
} 

.card{
    box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
    cursor: pointer;
}
.title{
    margin-top: 120px;
}
.overflow{
    overflow: hidden;
}
.card:hover .kenburns-top{animation:kenburns-top .5s ease-out both}
@keyframes kenburns-top{0%{transform:scale(1) translateY(0);transform-origin:50% 16%}100%{transform:scale(1.25) translateY(-15px);transform-origin:top}}
.card-body{
    padding: 30px !important;
}
.border{
    width: 20%;
    margin-top: 20px;
    margin-bottom: 30px;
}
</style>
