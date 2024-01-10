<template>
    <article class="quadrato">

        <img :src="getImagePath(`../assets/${immagine}`) " alt="immagine prodotto">
       

        <p class="oggetto">
            {{ oggetto }}
        </p>

       

    </article>
</template>
<script>
export default {
    name: 'PrimiQuattro',

    props: [
        'immagine',
        'oggetto',
        
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
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;


.oggetto{
    font-size: 15px;
    margin-top: 20px;

}



    
</style>