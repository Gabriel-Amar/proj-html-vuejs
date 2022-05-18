<template>
    <footer>
        <div class="container">
            <div class="row my-3">
                
                <div class="col-lg-4 p-5">
                    <div class=" input-group mb-3">
                        <input type="text" class="form-control" placeholder="Subscribe to our newsletter" aria-label="Recipient's username" aria-describedby="button-addon2">
                        <button class="btn btn-outline-secondary px-4 border-0" type="button" id="button-addon2">Register</button>
                    </div>
                </div>
                <div class="col-lg-8 p-5">
                    <div class="text ">
                        <p class="color"> <span class="colored">Insights is Picwik </span> University's thought leadership publication for sharing knowledge on management,technology and innovation.</p>
                        <p class="text-light">Take me there ></p>
                    </div>
                </div>
            </div>
            
        <section>
            <h2>Contact Us</h2>
            <ul>
                <li v-for="(item, index) in links1" :key="index">
                    
                    {{item.testo}}
                </li>
            </ul>
        </section>

        <section>
            <h2>Support Us</h2>
            <ul>
                <li v-for="(item, index) in links2" :key="index">
                    {{item.testo}}
                </li>
            </ul>
        </section>

        <section>
            <h2>Explore</h2>
            <ul>
                <li v-for="(item, index) in links3" :key="index">
                    {{item.testo}}
                </li>
            </ul>
        </section>

        <section>
            <h2>Visit</h2>
            <ul>
                <li v-for="(item, index) in links4" :key="index">
                    {{item.testo}}
                </li>
            </ul>
        </section>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'AppFooter',
    data(){
        return{
            links1:[
                {
                    testo: "900 Wood Street, MI New York 48607",
                },
                {
                    testo: "+56 345 678 000-09",
                },
                {
                    testo: "info@example.com",
                },
            ],
            links2:[
                {
                    testo: "Privacy",
                },
                {
                    testo: "Terms",
                },
                {
                    testo: "Cookie Policy",
                },
                {
                    testo: "Sitemap",
                },
            ],
            links3:[
                {
                    testo: "Accomodation"
                },
                {
                    testo: "Arts Academics"
                },
                {
                    testo: "Central Services"
                },
                {
                    testo: "Conferences and Evens"
                },
                {
                    testo: "Food and Drinks"
                },
            ],
            links4:[
                {
                    testo: "Admission"
                },
                {
                    testo: "Contact Us"
                },
                {
                    testo: "FAQs"
                },
                {
                    testo: "Request Information"
                },
                {
                    testo: "Privaacy Notice"
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">
@import "../assets/style/general.scss";
@import "../assets/style/vars.scss";

    footer{
        background-color: $ac-blue;
        background-repeat: no-repeat;
        height: 550px;
        background-position: center;
        background-size: cover;
        
    section{
        float: left;
        margin-right: 100px;
        margin-top: 60px;
        margin-left: 20px;
    }
    }
    ul li {
        cursor: pointer;
        color: $ac-foot;
        margin-bottom: 7px;

    }
    h2{
        font-weight: bold;
        color: $ac-white;
        margin-bottom: 20px;
    }
    li:before{
      content: ">";
    }
    ul{
      padding: 0 !important;
      list-style-type: none;
    }
    input{
        padding: 17px !important;
        border-top-left-radius: 0 !important;
        border-bottom-left-radius: 0 !important;
    }
    button{
        background-color: $ac-salmon !important;
        color: white !important;
        
    }
    .color{
        color: $ac-foot;
    }
    .colored{
        font-weight: 600;
        color: $ac-salmon;
        display:inline-block;
        border-bottom:0.1px solid white;
        padding-bottom:1px;
    }
    .row{
        align-items: center !important;
            box-shadow: rgba(0, 0, 0, 0.2) 0px 7px 29px 0px;

    }
</style>
