<template>
    <footer>
        <div class="container">
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
        height: 430px;
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
        color: gray;
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
</style>
