<template lang="">
    <article>
        <img src="" alt="">
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
    
}
</script>
<style lang="">
    
</style>