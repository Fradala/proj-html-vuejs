<template>
    <article class="quadrato">

        <img :src="getImagePath(`../assets/${immagine}`) " alt="immagine prodotto">
       

        <p>
            {{ oggetto }}
        </p>

    </article>
</template>
<script>
export default {
    name: 'PrimiQuattro',

    props: [
        'immagine',
        'oggetto'
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

    
    
};
</script>
<style lang="scss">


.quadrato{
    display: flex;
    
}
    
</style>