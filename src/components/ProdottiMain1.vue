<template >
    <section>
        <PrimiQuattro class="quadrati" v-for="prodotto in prodotti"
            :immagine="prodotto.foto" :oggetto="prodotto.oggetto"
        />

        <img src="../assets/images/product-9-150x150.jpg" alt="">
    </section>
</template>
<script>

import PrimiQuattro from './PrimiQuattro.vue';



export default {
    name: 'ProdottiMain1',

    components: {
        PrimiQuattro,
    },

    data () {
        return {
            prodotti: [
                {
                    foto: '../assets/images/product-9-150x150.jpg',
                    oggetto: 'Bed (1)',
                },
                {
                    foto: '../assets/images/product-3-150x150.jpg',
                    oggetto: 'Food (6)',
                },
                {
                    foto: '../assets/images/product-2-150x150.jpg',
                    oggetto: 'Toys (6)',
                },
                {
                    foto: '../assets/images/product-4-150x150.jpg',
                    oggetto: 'Transport (6)',
                },
            ],

           

            
        }
    }
    
}
</script>
<style lang="scss">
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

.quadrati{
    display: flex;
    flex-direction: row;
    width: calc((100% / 4) - 10px);
    margin-right: 5px;
    margin-left: 5px;
    margin-top: 10px;
    flex-wrap: nowrap;
}
    
</style>