<template lang="">
    <section class="container-fluid">
        <div class="row">
            <div class="contenitore-header d-flex justify-content-around p-2">
                <div>
                    <img src="../assets/images/dark-pet-logo-2x.png" alt="logo">
                </div>
                <div>
                    <input class="me-4" type="search" placeholder="Search...">
                </div>
                <div>
                    <p>
                        Questions? Call us: 1.800.123.4567
                    </p>
                </div>
                <div>
                    <i class="fa-solid fa-bag-shopping me-2"></i>
                    <i class="fa-regular fa-user"></i>

                </div>
            </div>
        </div>
        <div class="row">
            <div>
                <ul class="nav d-flex col-12 justify-content-center p-2">
                    <li>
                        Home <i class="fa-solid fa-chevron-down"></i>
                    </li>
                    <li>
                        Shop <i class="fa-solid fa-chevron-down"></i>
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
                        Shop by brand <i class="fa-solid fa-chevron-down"></i>
                    </li>
                </ul>
            </div>
           

        </div>
    </section>
    
    <article class="jumbo container-fluid">
            <div class="row">
                <div class="d-flex justify-content-around mt-2">
                    <p><i class="fa-regular fa-map me-1"></i> International Shipping Service</p>
                    <p><i class="fa-regular fa-clock me-1"></i>See our store hours and service</p>
                    <p><i class="fa-solid fa-check me-1"></i>We price match to give the best deals</p>
                </div>
            </div>
            <div class="jumbotron row">
                <div class="">
                    <h4 class="text-uppercase">find the best animal supplies</h4>
                    <p class="testo-lungo"> We know animals are a <br>
                        part of your family, let us <br>
                        hel take care of them
                    </p>
                    <button>
                        Learn more about us
                    </button>
                </div>
              

            </div>
            <div class="d-flex">
                <img class="croccantini" src="../assets/images/food-transparent-5-200x112.png" alt="croccantini">
                <p class="testo-croccantini mt-5">
                    Get $25 OFF your first purchese of our homemade pet food!
                </p>
            </div>

        </article>

</template>
<script>
export default {
    name: 'AppHeader',
}
</script>
<style lang="scss">
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

.contenitore-header{
    border-bottom: 1px solid black;
    width: 80%;
    margin: auto;

    img{
        width: 200px;
    }

    input{
        border-radius: 20px;
        border: none;
        font-size: 15px;
        background-color: #ebebeb;
        
    }
    p{
        font-size: 13px;
    }
}

.nav{
    font-size: 10px;
}


ul{
    list-style-type: none;


    li{
        margin-right: 10px;
    }
}

.jumbo{
    color: white;
    background-color: #1e3120;
    height: 650px ;


    .jumbotron{
        background-image: url(../assets/images/banner-5-2x-scaled.jpg);
        height: 500px;
        background-size: cover;
        background-position: center center;
        background-repeat: no-repeat;
        display: flex;
        align-items: center;
        padding: 2rem;

        h4{
            font-size: 10px;
        }

        .testo-lungo{
            font-size: 30px;
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

        }
        
    }

    p{
        font-size: 10px;
        
    }


}

.croccantini{
    width: 200px;
    margin-left: 200px;
}

.testo-croccantini{
    color: white;
    font-size: 15px;
}

    
</style>