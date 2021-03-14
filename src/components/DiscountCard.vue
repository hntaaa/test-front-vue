<template>
  <div id="cards">
    <img :src="resolve_img_url(picture_src)" />
  </div>
</template>
<script>
export default {
  name: 'DiscountCard',
  props: {
    picture_src: String,
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
    #cards img{
        width: 250px;
        border-radius: 10px;
    }
</style>