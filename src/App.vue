<template lang="">

  <AppHeader/>
  <AppMain/>
  <AppFooter/>

</template>
<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'app',
  components: {
    
    AppHeader,
    AppMain,
    AppFooter,
  },

  
  
}
</script>
<style lang="scss">
@use './styles/general.scss' as *;
  
</style>