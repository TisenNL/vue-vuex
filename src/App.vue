<template>
  <div id="app">

    <div class="jumbotron jumbotron-fluid">
      <div class="container">
        <h1 class="display-4">Vuex</h1>
        <p class="lead">Padrão de Gerenciamento de Estado Centralizado no Vue.</p>
      </div>
    </div>

    <div class="container">

      <AppContador />

    </div>

  </div>
</template>

<script>

import AppContador from '@/components/AppContador.vue'

export default {
  components: {
    AppContador
  }
    
}
</script>