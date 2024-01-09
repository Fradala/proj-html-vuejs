<template>
    <section>
        <div v-for="prodotto in prodotti">
            <img :src="prodotto.foto" alt="prodotto">
            <p>
                {{ prodotto.oggetto }}
            </p>

        </div>
    </section>
</template>
<script>
export default {
    
    data() {
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
    },

    props: {
       prodotti: {
            type: Array,
            required: true,
       }
    

    },
    
}
</script>
<style lang="scss">
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;
    
</style>