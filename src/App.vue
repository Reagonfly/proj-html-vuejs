<script>
import AppHeader from './components/AppHeader.vue';
import AppServices from './components/AppServices.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components:{
    AppHeader,
    AppFooter,
    AppServices
  }
}
</script>

<template lang="">

    <AppHeader />
    <AppServices />
    <AppFooter />

</template>

<style lang="scss">
  @use './styles/generals.scss' as *;
  
</style>
