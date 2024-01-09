<template>
    <div class="titoletto text-center mt-5">
        <h1 class="fs-4 mb-3">
            Browse by category
        </h1>
        <p class="sottotitolo">
            Augue purus et, ticidii cpododicic mamams, at bwh wbdwdb hb hbdwb hjdbwjdb <br> inteidb ehdehe deheh eehbbebue uebuebue ddbwb dwdbwb.
        </p>
    </div>
    <section class="container">
        <!--qui ci vanno le 4 card-->
        <PrimeQuattroCards/>
        <!--qui ci sono le 3 caselle per il cibo-->
       <article class="row d-flex mt-5">
            <div class="casella  text-center">
                <h2>
                    Kibble
                </h2>
                <p>
                    Dry dog food
                </p>
                <img src="../assets/images/food-transparent-18.png" alt="crocchette per cani">
                <button>Shop kibble food</button>
            </div>
            <div class="casella  text-center">
                <h2>
                    Moist
                </h2>
                <p>
                    Canned dog food
                </p>
                <img src="../assets/images/food-transparent-17.png" alt="crocchette per cani">
                <button>Shop moist food</button>
            </div>
            <div class="casella  text-center">
                <h2>
                    Frozen
                </h2>
                <p>
                    Freze-Dried dog food
                </p>
                <img src="../assets/images/food-transparent-16.png" alt="crocchette per cani">
                <button>Shop frozen food</button>
            </div>
       </article>

        <!--qui c'è il banner cane e gatto-->
       <article class="gatto-cane row mt-5 text-center">
            <div>
                <h3 class="text-uppercase">
                    find the best animal supplies
                </h3>
                <p class="fs-2">
                    New arrivals weekly
                </p>
                <button>Learn more about us</button>
            </div>

       </article>

       <article class="row best-seller mt-5">
            <section class=" d-flex justify-content-between">
                <div>
                    <p>
                        All-time best seller 
                    </p>
                    <p class="testo-grande">
                        Items everyone loves
                    </p>
                </div>
                <div>
                    <button class="mt-3">
                        View all products
                    </button>
                </div>
            </section>
       </article>
       <SecondeQuattroCards/>
    </section>
    <section class="testimonials">
        <article class="container mt-5">
            <h4 class="text-center titolo-testimonials pt-5">
                Users testimonials
            </h4>
            <div class="d-flex text-center pt-4">
                <div>
                    <img src="../assets/images/avatar-3-200x200.jpg" alt="foto testimonials">
                    <p class="descrizione-testimone p-2">
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                        Ipsum nisi magnam ab  
                        
                    </p>
                    <p>
                        il nome del testimone 
                    </p>
                </div>
                <div>
                    <img src="../assets/images/avatar-1-200x200.jpg" alt="foto testimonials">
                    <p class="descrizione-testimone p-2">
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                        Ipsum nisi magnam ab  
                    </p>
                    <p>
                        il nome del testimone 
                    </p>
                </div>
                <div>
                    <img src="../assets/images/avatar-4-200x200.jpg" alt="foto testimonials">
                    <p class="descrizione-testimone p-2">
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                        Ipsum nisi magnam ab  
                    </p>
                    <p>
                        il nome del testimone 
                    </p>
                </div>

            </div>

        </article>


    </section>
   <article>
        <div class="posta p-5">
            <h4 class="mb-4">
                Join your newsletter
            </h4>

            <p class="mb-4">
                voendkd dekiddjd dejdjdhd djdjd ejejdj dddj <br> 
                shsjssj dhdjd bjdjhdd
            </p>

            <div class="d-flex">
                <input class="me-4" type="search" placeholder="insert your email ...*">
                <button>subscribe</button>
            </div>


        </div>
   </article>
    <div class="text-center mt-5">
        <h4>
            Get the best tips & tricks
        </h4>
        <p class="fs-7">
            Recent article
        </p>
    </div>
    <!--
    <section>quattro cards</section>-->
    <TerzeQuattroCards/>

    <section class="due-animali d-flex text-center">
        <div class="cane">
            <h5 class="text-uppercase">
                find the best animals supplies
            </h5>

            <p>
                Popular accessories
            </p>

            <button>
                View all toys accessories
            </button>

        </div>
        <div class="gatto">
            <h5 class="text-uppercase">
                find the best animals supplies
            </h5>

            <p>
                Popular accessories
            </p>

            <button>
                View all toys accessories
            </button>

        </div>
       
    </section>
    <section class="altre-info">
            <div class="container">
                <div class="d-flex justify-contente-between">
                    <div class="icone">
                        <i class="fa-solid fa-truck"></i>
                        <p>
                            Free worldwild dliveries
                        </p>
                    </div>
                    <div class="icone">
                        <i class="fa-regular fa-map"></i>
                        <p>
                            Find store near you
                        </p>
                    </div>
                    <div class="icone">
                        <i class="fa-solid fa-dollar-sign"></i>
                        <p>
                            Best prices guarranteed
                        </p>
                    </div>
                    <div class="icone">
                        <i class="fa-solid fa-credit-card"></i>
                        <p>
                            All credit car accepted
                        </p>
                    </div>

                </div>
            </div>


    </section>
    <section class="container">
        <div class="text-center mt-5">
            <h4>
                New products arrival
            </h4>
            <p>
                Latest products
            </p>

        </div>


        <div class="d-flex sei-prodotti">
            <div>
                <img src="../assets/images/product-8-200x200.jpg" alt="letto per cani">
                <p class="descrizione-ogg text-center mt-3">
                    Colorful ball set
                </p>
                <p class="prezzo text-center">
                    $29.00
                </p>

            </div>
            <div>
                <img src="../assets/images/product-3-200x200.jpg" alt="letto per cani">
                <p class="descrizione-ogg text-center mt-3">
                    Dog bone
                </p>
                <p class="prezzo text-center">
                    $28.00 - $18.00
                </p>

            </div>
            <div>
                <img src="../assets/images/product-2-200x200.jpg" alt="letto per cani">
                <p class="descrizione-ogg text-center mt-3">
                    Colore per bed
                </p>
                <p class="prezzo text-center">
                    $18.00 - $26.00
                </p>

            </div>
            <div>
                <img src="../assets/images/product-4-200x200.jpg" alt="letto per cani">
                <p class="descrizione-ogg text-center mt-3">
                    Animal transport bag
                </p>
                <p class="prezzo text-center">
                    $29.00
                </p>

            </div>
            <div>
                <img src="../assets/images/product-5-200x200.jpg" alt="letto per cani">
                <p class="descrizione-ogg text-center mt-3">
                    Animal transport cage
                </p>
                <p class="prezzo text-center">
                    $35.00
                </p>

            </div>
            <div>
                <img src="../assets/images/product-10-200x200.jpg" alt="letto per cani">
                <p class="descrizione-ogg text-center mt-3">
                    Closable cat litter
                </p>
                <p class="prezzo text-center">
                    $16.00 
                </p>

            </div>

        </div>
        
    </section>

    
        
    
  
</template>
<script>

import PrimeQuattroCards from './PrimeQuattroCards.vue';
import SecondeQuattroCards from './SecondeQuattroCards.vue';
import TerzeQuattroCards from './TerzeQuattroCards.vue';
export default {
    name: 'AppMain',

    components: {
        PrimeQuattroCards,
        SecondeQuattroCards,
        TerzeQuattroCards,

    }

    
    
}
</script>
<style lang="scss">
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;


.titoletto{

    h1{
        font-family: 'Merriweather', serif;
    }

    .sottotitolo{
        font-size: 10px;
        font-family: 'Libre Franklin', sans-serif;
    }
}

.container{
    width: 80%;
    margin: auto;

   

   

    .casella{
        background-color: #1e3120 ;
        margin-right: 5px;
        width: calc((100% / 3) - 10px);

        


        
        
        

        h2{
            color: white;
            margin-top: 30px;
            font-family: 'Merriweather', serif;
        }
        p{
            color:#539f5b ;
        }

        button{
            border-radius: 20px;
            background-color: #539f5b;
            color: white;
            padding: 5px 10px;
            border: none;
            font-size: 10px;
            margin-bottom: 30px;
        }
        img{
            width:80%;
        }
    }

    .gatto-cane{
        background-image:url(../assets/images/banner-3-2x-scaled.jpg) ;
        height: 300px;
        background-size: cover;
        background-position: center center;
        background-repeat: no-repeat;
        opacity: 90%;

        color: white;
        display: flex;
        align-items: center;


        h3{
            font-size: 10px;
        }

        p{
            font-family: 'Merriweather', serif;
        }

        button{
            border-radius: 20px;
            background-color: white;
            color: black;
            padding: 5px 10px;
            border: none;
            font-size: 10px;
            margin-bottom: 30px;

            &:hover {
                background-color: #539f5b;
                color: white;
            }

        }
    }

    .best-seller{


        p{
            font-family: 'Libre Franklin', sans-serif;
            font-size: 10px;
        }

        .testo-grande{
            font-size: 20px;
            font-family: 'Merriweather', serif;
        }

        button{
            border-radius: 20px;
            background-color: #539f5b;
            color: white;
            padding: 5px 10px;
            border: none;
            font-size: 10px;
            margin-bottom: 30px;

            &:hover {
                background-color: #1e3120;
            }
        }
    }
    
    



}

.testimonials{
    background-color: #1e3120;
    
    height: 350px;

    //position: relative;

    .titolo-testimonials{
        font-family: 'Merriweather', serif;
        font-size: 25px;
        color: white;
        
        
    }

    

   

    img{
        width: 50px;
        border-radius: 50%;
        margin-bottom: 10px;
        
        
    }

    .descrizione-testimone{
        font-size: 13px;
        color: white;
        
    }

    p{
        font-family: 'Libre Franklin', sans-serif;
        font-size: 10px;
        color: #cacbca;
    }

        
}

.posta{
    background-image: url(../assets/images/banner-7-2x-scaled.jpg);
    height: 250px;
    width: 80%;
    margin: auto;
    background-size: contain;
    background-position: center center;
    background-repeat: no-repeat;

    //position: absolute;
    //left: 10%;
    //top: 250%;



    h4{
        font-family: 'Merriweather', serif;
    }

    p{
        font-family: 'Libre Franklin', sans-serif;
        font-size: 10px;
    }

    input{
        border-radius: 20px;
        border: none;
        font-size: 15px;
        background-color: #ebebeb;
        
    }

   button{
        border-radius: 20px;
        background-color: #539f5b;
        color: white;
        border: none;
        font-size: 10px;
        padding: 5px 20px;

   }

  

    
}

.due-animali{

    .cane{
        background-image: url(../assets/images/banner-8-2x.jpg);
        width: 50%;
        height: 300px;
        background-size: cover;
        background-position: center center;
        background-repeat: no-repeat;
        opacity: 90%;
        color: white;

        h5{
            font-family: 'Libre Franklin', sans-serif;
            font-size: 10px;
            margin-top: 100px;
        }
        p{
            font-family: 'Merriweather', serif;
            font-size: 30px;
        }
        button{
            border-radius: 20px;
            background-color: white;
            color: black;
            border: none;
            font-size: 10px;
            padding: 5px 20px;

        }
    }

    .gatto{
        background-image: url(../assets/images/banner-9-2x.jpg);
        width: 50%;
        height: 300px;
        background-size: cover;
        background-position: center center;
        background-repeat: no-repeat;
        opacity: 90%;
        color: white;

        h5{
            font-family: 'Libre Franklin', sans-serif;
            font-size: 10px;
            margin-top: 100px;
        }
        p{
            font-family: 'Merriweather', serif;
            font-size: 30px;
        }

        button{
            border-radius: 20px;
            background-color: white;
            color: black;
            border: none;
            font-size: 10px;
            padding: 5px 20px;

        }


    }
}

.altre-info{
    background-color: #1e3120;
    height: 150px;
    width: 100%;

    .icone{
        margin-top: 50px;
        color: white;
        text-align: center;
        width: 25%;

       
    }
    i{
        margin-bottom: 10px;
        font-size: 30px;
    }
    p{
        font-size: 10px;
        color: #cacbca;
    }

    
    


}


.sei-prodotti{

    display: flex;
    flex-wrap: wrap;
    div{
        width: calc(100% / 3);
    }

    .descrizione-ogg{
        font-size: 15px;
    }

    .prezzo{
        font-size: 10px;
    }
}

    
</style>