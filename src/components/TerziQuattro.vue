<template lang="">
    <article>
        <img :src="getImagePath(`../assets/${immagine}`) " alt="immagine prodotto">
        <p class="testo">
            {{ testo }}
        </p>
        <p class="data">
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
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

.testo{
    font-size: 10px;

}

.data{
    font-size: 5px;
}



    
</style>