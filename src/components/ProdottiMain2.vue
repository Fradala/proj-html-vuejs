<template lang="">
     <section class="quadrati">
        <SecondiQuattro  v-for="prodotto in prodotti"
            :immagine="prodotto.foto" :oggetto="prodotto.prodotto" :prezzo="prodotto.price"
        />

        
    </section>
</template>
<script>
import SecondiQuattro from './SecondiQuattro.vue';
export default {

    components: {
        SecondiQuattro,
    },

    data() {
        return {
            prodotti: [
                {
                    foto: '../assets/images/product-21-200x200.jpg',
                    prodotto: 'Transport cage',
                    price: '$25,00',
                },
                {
                    foto: '../assets/images/product-20-200x200.jpg',
                    prodotto: 'Dog leash',
                    price: '$25,00',
                },
                {
                    foto: '../assets/images/product-16-200x200.jpg',
                    prodotto: 'Animal trasport cage',
                    price: '$25,00',
                },
                {
                    foto: '../assets/images/product-11-200x200.jpg',
                    prodotto: 'Colorful cat leash',
                    price: '$25,00',
                },
            ]
        }
    },
    
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
    flex-wrap: nowrap;
}
    
</style>