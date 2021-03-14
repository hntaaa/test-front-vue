<template>
  <div id="app">
    <Header></Header>
    <div class="container">
      <Intro/>
      <Discount />
      <Insurance/>
      <Autoparts />
      <Help />
      <Autolawyer />
      <Table />
      <Penalty />
      <Credit />
    </div>
    <Footer />
  </div>
</template>

<script>


import Header from '@/components/Header.vue'
import Intro from '@/components/Intro.vue'
import Discount from '@/components/Discount.vue'
import Insurance from '@/components/Insurance.vue'
import Autoparts from '@/components/Autoparts.vue'
import Help from '@/components/Help.vue'
import Autolawyer from '@/components/Autolawyer.vue'
import Table from '@/components/Table.vue'
import Penalty from './components/Penalty.vue'
import Credit from './components/Credit.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    Intro,
    Discount,
    Insurance,
    Autoparts,
    Help,
    Autolawyer,
    Table,
    Penalty,
    Credit,
    Footer
  }
}
</script>

<style>
  .container{
    max-width: 1170px;
    margin: 0 auto;
  }
  body{
    background: #111320;
    margin: 0;
    padding: 0;
  }
  
</style>
