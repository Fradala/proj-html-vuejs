<template >
    <section>
        <PrimiQuattro class="quadrati" v-for="prodotto in prodotti"
            :immagine="prodotto.foto" :oggetto="prodotto.oggetto"
        />

        
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
                    foto: '..assets/images/product-9-150x150.jpg',
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
    width: calc((100% / 4) - 10px);
    flex-wrap: wrap;
}
    
</style>