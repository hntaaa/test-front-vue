<template>
  <div class="discount">
      <div class="title">
          <h2>Акции</h2>
          <a href="#">Все</a>
      </div>
      <div class="cards">
        <DiscountCard  picture_src='card1.jpg' />
        <DiscountCard  picture_src='card3.jpg' />
        <DiscountCard  picture_src='card2.jpg' />
        <DiscountCard  picture_src='card4.jpg' />
      </div>
    
  </div>
</template>

<script>
import DiscountCard from '@/components/DiscountCard.vue'
export default {
  name: 'Discount',
  components: {
    DiscountCard
  }
}
</script>

<style>
    .discount{
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