<template>
   <div id="app">
			<product-list-one></product-list-one>
			<product-list-two></product-list-two>
   </div>
</template>

<script>
import ProdectListOne from '@/components/ProductListOne'
import ProdectListTwo from '@/components/ProductListTwo'

export default {
  name:'app',
  components:{
  	'product-list-one':ProdectListOne,
		'product-list-two':ProdectListTwo
  },
  data(){
  	return {
		
	}

  }
}
</script>

<style>
</style>
