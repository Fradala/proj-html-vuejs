<template>
    <article>

        <!--<img :src="getImagePath(`../assets${imageName}`)" alt="">-->
       

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

    /*data() {
        return {
            imageName: 'immagine'
        }
    },

    methods: {
        getImagePath: functionI(imgPath){
            return new URL(imgPath, import.meta.url).href;
        }
    },*/

    
    
}
</script>
<style lang="">
    
</style>