<template>
    <div class="text-center mt-5">
        <h1 class="fs-4 mb-3">
            Browse by category
        </h1>
        <p class="sottotitolo">
            Augue purus et, ticidii cpododicic mamams, at bwh wbdwdb hb hbdwb hjdbwjdb <br> inteidb ehdehe deheh eehbbebue uebuebue ddbwb dwdbwb.
        </p>
    </div>
    <section class="container">
        <!--qui ci vanno le 4 card-->

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
                <p>
                    Items everyone loves
                </p>
            </div>
            <div>
                <button>View all products</button>
            </div>
        </section>
            
       </article>


    </section>
    
        
    
  
</template>
<script>
export default {
    name: 'AppMain',
}
</script>
<style lang="scss">
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

.container{
    width: 80%;
    margin: auto;

    .sottotitolo{
    font-size:15px;
    }

   

    .casella{
        background-color: #1e3120 ;
        margin-right: 5px;
        width: calc((100% / 3) - 10px);
        
        
        

        h2{
            color: white;
            margin-top: 30px;
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

        button{
            border-radius: 20px;
            background-color: white;
            color: black;
            padding: 5px 10px;
            border: none;
            font-size: 10px;
            margin-bottom: 30px;

        }
    }
    



}




    
</style>