<template>
  <div>
    <h1 class="mainTitle">{{ title }}</h1>
  </div>
  <AppHero/>
</template>

<script>
import AppHero from './components/AppHero.vue';

export default {
  data () {
    
    return {
      title: "La mia prima app con Vite!"
    }
  },
  components:{
    AppHero
  }
}
</script>

<style lang="css" scoped>
  .mainTitle{
    color: red;
    text-align: center;
    padding-top: 12px;
  }
</style>