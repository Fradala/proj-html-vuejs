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
        margin-right: 10px;
        width: calc((100% / 3) - 20px);
        
        
        

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
    }

    img{
        width:80%;
    }



}




    
</style>