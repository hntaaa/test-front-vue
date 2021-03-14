<template>
  <div class="credit">
      <div class="title">
          <h2>Автокредиты</h2>
          <a href="#">Все</a>
      </div>
      <div class="cards">
        <CreditCard  picture_src='creditcard1.jpg' picture_desc="Компания 1"/>
        <CreditCard  picture_src='creditcard2.jpg' picture_desc="Компания 2" />
      </div>
    
  </div>
</template>

<script>
import CreditCard from '@/components/CreditCard.vue'
export default {
  name: 'Credit',
  components: {
    CreditCard
  }
}
</script>

<style>
    .credit{
        margin-top: 3rem;
        display: flex;
        flex-direction: column;
    }
    .title{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .title h2{
        text-transform: uppercase;
        font-weight: bold;
        color: white;
        font-size: 1rem;
        letter-spacing: 2px;
    }

    .title a{
        text-transform: capitalize;
        background: #22223a;
        text-decoration: none;
        color: white;
        text-align: center;
        padding: 0.5rem 1.5rem;
        letter-spacing: 2px;
    }
    .cards{
        margin-top: 1rem;
        display: flex;
        justify-content: space-between;    
    }
</style>