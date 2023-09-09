<template>
  <div class="home">
    <ListaProdutos/>
  </div>
</template>

<script>
// @ is an alias to /src
import ListaProdutos from '@/components/Produtos/ListaProdutos.vue'

export default {
  name: 'HomeView',
  components: {
    ListaProdutos
  }
}
</script>
