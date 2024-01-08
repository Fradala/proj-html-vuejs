<template lang="">
    <section class="container-fluid">
        <div class="row">
            <div class="contenitore-header d-flex justify-content-around p-2">
                <div>
                    logo
                </div>
                <div>
                    logo
                </div>
                <div>
                    logo
                </div>
                <div>
                    logo
                </div>
            </div>
        </div>
        <div class="row">
            <div>
                <ul class="d-flex col-12 justify-content-center p-2">
                    <li>
                        Home
                    </li>
                    <li>
                        Shop
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
                        Shop by brand
                    </li>
                </ul>
            </div>
           

        </div>
    </section>
    
    <article class="jumbo container-fluid">
            <div class="row">
                <div class="d-flex justify-content-around">
                    <p>ciao</p>
                    <p>ciao</p>
                    <p>ciao</p>
                </div>
            </div>
            <div>
                
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
}

ul{
    list-style-type: none;


    li{
        margin-right: 10px;
    }
}

.jumbo{
    border: 1px solid red;
}

    
</style>