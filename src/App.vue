<template>
  <div id="app">
    <product-list-one></product-list-one>
    <product-list-two></product-list-two>
  </div>
</template>

<script>
import ProductListOne from './components/product-list-one.vue'
import ProductListTwo from './components/product-list-two.vue'
export default {
  name: 'app',
  components:{
    'product-list-one': ProductListOne,
    'product-list-two': ProductListTwo
  },
  data () {
    return {
      // products:[
      //     {name:'Banana Skin',price:20},
      //     {name:'Shiny Star',price:40},
      //     {name:'Green Shells',price:60},
      //     {name:'Red Shells',price:80}
      // ]
    }
  }
}
</script>


<style>

</style>
