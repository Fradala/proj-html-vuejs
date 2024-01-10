<template >
    <section class="quadrati">
        <PrimiQuattro v-for="prodotto in prodotti"
            :immagine="prodotto.foto" :oggetto="prodotto.oggetto"
        />

        
    </section>
</template>
<script>

import PrimiQuattro from './PrimiQuattro.vue';



export default {
   

    components: {
        PrimiQuattro,
    },

    data () {
        return {
            prodotti: [
                {
                    foto: '../assets/images/product-9-200x200.jpg',
                    oggetto: 'Bed (1)',
                },
                {
                    foto: '../assets/images/product-3-200x200.jpg',
                    oggetto: 'Food (6)',
                },
                {
                    foto: '../assets/images/product-2-200x200.jpg',
                    oggetto: 'Toys (6)',
                },
                {
                    foto: '../assets/images/product-4-200x200.jpg',
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
    justify-content: space-evenly;
    align-items: center;
    margin: 0 auto;
    flex-wrap: wrap;
   
}
    
</style>