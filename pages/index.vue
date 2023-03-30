<template>
 <div class="container mx-auto  my-2 ">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css" rel="stylesheet">
<top-nav></top-nav>
<nav-bar></nav-bar>
<date-card></date-card>
<message/>
<information></information>
<charge-slider/>
<rate></rate>
<product></product>
 </div>
</template>

<script>
import product from '~/components/product.vue'




export default {
  components: { product },
  

  name: 'IndexPage'
}
</script>
<style>

</style>
