<template>
    <section>
        <TerziQuattro class="quadrati" v-for="prodotto in prodotti"
            :immagine="prodotto.foto" :testo="prodotto.testo" :data="prodotto.sottoTesto"
        />

        
    </section>
</template>
<script>

import TerziQuattro from './TerziQuattro.vue';
export default {

    components: {
        TerziQuattro,
    }, 
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
                    testo: 'Stop cats from scratching furniture',
                    sottoTesto: 'April 21st, 2020',
                },
                {
                    foto: '../assets/images/blog-3-200x200.jpg',
                    testo: 'Where to buy the best pet food',
                    sottoTesto: 'April 21st, 2020',
                },
                {
                    foto: '../assets/images/blog-4-200x200.jpg',
                    testo: 'Proper care for your pet toys',
                    sottoTesto: 'April 21st, 2020',
                },
            ]
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