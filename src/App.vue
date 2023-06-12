<template>
  <div class="home__page">
    <Header/>
    <main>
      <MainSection1/>
      <MainSection2/>
    </main>
  </div>
</template>

<script>
import Header from './components/home-page/header.vue'
import MainSection1 from './components/home-page/main/section1__main.vue'
import MainSection2 from './components/home-page/main/section2__main.vue'
export default{
  data(){
    return{

    }
  },
  components:{
    Header,
    MainSection1,
    MainSection2,
  }
}

</script>
  

