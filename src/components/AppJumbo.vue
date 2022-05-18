<template>
    <div>
        <img src="../assets/img/02_Landing-Page.jpg" alt="">
        <span class="" >Professional Development For Coaches And Leaders</span>
        <button type="button" class="btn btn-outline-dark rounded-0 ">Learn More</button>
    </div>
</template>

<script>
export default {
    name: 'AppJumbo',
}
</script>

<style scoped lang="scss">
@import "../assets/style/general.scss";
@import "../assets/style/vars.scss";


img{
    width: 100%;
    position: relative;
}
span, button{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 3rem;
    text-align: center;
    font-family: $jb-family;
}
button{
    margin-top: 140px;
    padding: 16px 48px !important;
}
button:hover{
    background-color: $ac-salmon !important;
    border-color: $ac-salmon !important;
}

</style>
