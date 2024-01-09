<template lang="">
   <section class="info-verdi text-start">
        <div class="container">
            <div class="quattro-info d-flex justify-content-between">
                <div class="quadrato">
                    <img src="../assets/images/mobile-light-pet-logo-2x.png" alt="logo">
                    <p class="mt-4">
                        1234 Avada Avenue Avadaville <br>
                        info@your-company.com <br>
                        Call us: (1) 2345678
                    </p>
                </div>
                <div class="quadrato">
                    <h5>
                        Shop by brand
                    </h5>
                    <ul class="lista">
                        <li>
                            Bed
                        </li>
                        <li>
                            Food
                        </li>
                        <li>
                            Toys
                        </li>
                        <li>
                            Transport
                        </li>
                    </ul>
                </div>

                <div class="quadrato">
                    <h5>
                        Useful links
                    </h5>
                    <ul class="lista">
                        <li>
                            My account
                        </li>
                        <li>
                            Orders
                        </li>
                        <li>
                            Checkout
                        </li>
                        <li>
                            Cart
                        </li>
                    </ul>
                </div>

                <div class=" quadrato carta-verde">
                    <p>
                        Subscribe to our <br>
                        newsletter
                    </p>
                    <input class="mb-4 me-3" type="search" placeholder="insert your email ...*">
                    <button>subscribe</button>

                </div>

            </div>
            <div>
                <ul class="contatti">
                    <li>
                        Home
                    </li>
                    <li>
                        About
                    </li>
                    <li>
                        Blog
                    </li>
                    <li>
                        Contact
                    </li>
                    <li>
                        Shop
                    </li>

                </ul>

                <div class="icone-social">
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-instagram"></i>
                    <i class="fa-brands fa-youtube"></i>


                </div>

            </div>

        </div>
        
        



   </section>
   <div class="striscia-nera">
            <p>
                @Copyright 2012 - 2020 | Avada Theme bynThemeFusion | All Rights Reserved | Powered by Wordpress
            </p>

   </div>
</template>
<script>
export default {
    name: 'AppFooter',
    
}
</script>
<style lang="scss">
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

.info-verdi{
    background-color: #1e3120;
    height: 500px;
    display: flex;
    justify-content: center;
    

    .quattro-info{
        border-bottom: 1px solid white;
        margin: auto;
        color: white;
        height: 300px;
        padding: 2rem;
        
        

    }

    .quadrato{
        width: 25%;
    }

    img{
        width: 140px;
        
    }

    input{
        border-radius: 20px;
        border: none;
        font-size: 10px;
        width: 100px;
        
    }

    button{
        border-radius: 20px;
        background-color: #539f5b;
        color: white;
        border: none;
        font-size: 10px;
        padding: 5px 20px;

    }

    .lista{
        text-align: start;
    }

    h5{
        font-size: 15px;
        margin-bottom: 20px;
        font-family: 'Merriweather', serif;
    }

    p{
        font-size: 13px;
        font-family: 'Libre Franklin', sans-serif;
        margin-bottom: 20px;
    }

    li{
        margin-bottom: 10px;
    }

    .carta-verde{
        padding: 1rem;
        background-color: #2d462f;
        color: white;
    }

    .contatti{
        display: flex;
        flex-direction: row;
        justify-content: center;
        color: white;
        margin-top: 20px;

       
    }

    .icone-social{
        color: white;
        text-align: center;

        .fa-brands{
            margin-right: 10px;
        }
    }

    

}

.striscia-nera{
        background-color: black;
        padding: 1rem;
        color: white;


        p{
            font-size: 10px;
            text-align: center;
            margin-top: 5px;
        }
}

    
</style>