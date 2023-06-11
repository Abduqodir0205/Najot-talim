<template>
  <div class="home__page">
    <main>
      <MainSection1/>
      <MainSection2/>
    </main>
  </div>
</template>

<script>
import MainSection1 from '../src/components/home-page/main/section1__main.vue'
import MainSection2 from '../src/components/home-page/main/section2__main.vue'
export default{
  data(){
    return{

    }
  },
  components:{
    MainSection1,
    MainSection2
  }
}
 
</script>

<style>
@import '../src/sass/style.scss';
</style>
