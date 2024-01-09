<template lang="">
    <div>
        <img src="../assets/images/blog-1-200x200.jpg" alt="">
    </div>
</template>
<script>
export default {

    data() {
        return {
            prodotti: [

                {
                    foto: '../assets/images/blog-1-200x200.jpg',
                    testo: 'How to loose leash walk your dog',
                    sottoTesto: 'April 21st, 2020',
                },
                {
                    foto: '../assets/images/blog-2-200x200.jpg',
                    oggetto: 'Stop cats from scratching furniture',
                    sottoTesto: 'April 21st, 2020',
                },
                {
                    foto: '../assets/images/blog-3-200x200.jpg',
                    oggetto: 'Where to buy the best pet food',
                    sottoTesto: 'April 21st, 2020',
                },
                {
                    foto: '../assets/images/blog-4-200x200.jpg',
                    oggetto: 'Proper care for your pet toys',
                    sottoTesto: 'April 21st, 2020',
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