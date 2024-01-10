<template lang="">
    <article>
        <img :src="getImagePath(`../assets/${immagine}`) " alt="immagine prodotto">
        <p>
            {{ testo }}
        </p>
        <p>
            {{ data }}
        </p>

        
    </article>
    
</template>
<script>
export default {

    name: 'TerziQuattro',

    props: [
        'immagine',
        'testo',
        'data',
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



    
</style>