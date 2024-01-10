<template lang="">
    <article>
        <img src="" alt="">
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
    
}
</script>
<style lang="">
    
</style>