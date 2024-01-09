<template lang="">
    <div>
        <img src="../assets/images/product-21-200x200.jpg" alt="">
        
    </div>
</template>
<script>
export default {

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