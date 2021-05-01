<template>
  <div class="header">
      <Logo/>
      <NavBar/>
      <SearchForm/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Logo } from '@/components/atoms'
import { NavBar, SearchForm } from '@/components/molecules'

export default defineComponent({
    components:{
        Logo,
        NavBar, 
        SearchForm
    }
})
</script>

<style lang="scss" scoped>
.header {
  width: 100%;
  display: grid; // vamos usar o display grid
  grid-template-columns: 160px repeat(2, auto); // e vamos criar 3 colunas. 1 de 160px e outras 2 geradas autoamticamente com o tamanho automatico
  align-items: center; // vamos alinhar os itens no centro (eixoY)
  justify-content: space-between; // gera um espaçamento entre cada item
} 
</style>
