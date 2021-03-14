<template>
  <div id="credit_cards">
      <div class="left">
        <img :src="resolve_img_url(picture_src)" />
        <div class="in-left">
            <h3>{{picture_desc}}</h3>
            <p>Ставка %</p>
        </div>
      </div>

      <div class="right">
        <a href="#"> Перейти на сайт</a>
      </div>

  </div>
</template>
<script>
export default {
  name: 'CreditCard',
  props: {
    picture_src: String,
    picture_desc: String
  },
  methods: {
    resolve_img_url: function (path) {
      let images = require.context('../assets/', false, /\.png$|\.jpg$/)
      return images("./"+path)
    }
  }
}
</script>

<style>
    #credit_cards img{
        width: 120px;
        height: 100px;
        border-radius: 70%;
        margin-right: 1rem;
    }
    #credit_cards{
        display: flex;
        justify-content: space-between;
        align-items: center;
        background: #22223a;
        width: 100%;
        height: 150px;
        margin-top: 1rem;
        border-radius: 10px;
        padding: 0 1rem; 
    }
    #credit_cards a{
        border-radius: 10px;
        font-size: 1rem;
        padding: 1rem 4rem;
        background-color: #00a847;
        text-decoration: none;
        color: white;
        letter-spacing: 2px;
        cursor: pointer;
        margin-left: 500px;
    }
    .left{
        display: flex;
        justify-content: center;
        align-items: center;
    }
    
    .in-left h3{
        color: white;
        font-size: 1rem;
        letter-spacing: 0.5px   ;
    }

    .in-left p{
        color: #00a847;
    }
</style>