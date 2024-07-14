<template>
  <div class="main-container">
    <H1>Gerenciador de pedidos:</H1>
    <Dashboard/>
  </div>
</template>

<script>
import Dashboard from '../components/Dashboard'

export default {
  name: 'Pedidos',
  components: {
    Dashboard
  }
}
</script>
