<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import AppCard from './components/AppCard.vue';



export default {
  components: {
    AppHeader,
    AppFooter,
    AppCard,
  }
}
</script>

<template>
  <AppHeader/>
  <main>
    <AppCard/>
    <AppFooter/>

  </main>
</template>

<style>

</style>