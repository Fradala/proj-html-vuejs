<template lang="">
    <article>
        <img :src="getImagePath(`../assets/${immagine}`) " alt="immagine prodotto">
        <p class="oggetto">
            {{ oggetto }}
        </p>
        <p class="prezzo">
            {{ prezzo }}
        </p>
    </article>
</template>
<script>
export default {

    name: 'SecondiQuattro',

    props: [
        'immagine',
        'oggetto',
        'prezzo',
    ],

    data() {
        return {
            imageName: 'immagine'
        };
    },

    methods: {
        getImagePath: function(imgPath) {
            return new URL(imgPath, import.meta.url).href;
        }
    }
    
}
</script>
<style lang="scss">
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

img{
    width: 100%;
}


.oggetto{
    font-size: 15px;
    font-family: 'Merriweather', serif;

}

.prezzo{
    font-size: 10px;
    font-family: 'Merriweather', serif;
}
    
</style>