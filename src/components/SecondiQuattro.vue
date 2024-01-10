<template lang="">
    <article>
        <img :src="getImagePath(`../assets/${immagine}`) " alt="immagine prodotto">
        <p>
            {{ oggetto }}
        </p>
        <p>
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
<style lang="">
    
</style>