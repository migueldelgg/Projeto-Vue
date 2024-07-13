<template>
  <div>
    <Banner />
    <div class="main-container">
      <h1>Monte o seu burger:</h1>
      <BurgerForm />
    </div>
  </div>
</template>

<script>
import Banner from '../components/Banner'
import BurgerForm from '../components/BurgerForm'

export default {
  name: 'HomeView',
  components: {
    Banner,
    BurgerForm
  }
}
</script>

<style scoped>
.main-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

h1 {
  margin: 0;
  padding: 10px 0;
}

.main-container > * {
  margin: 0;
  padding: 0;
}
</style>
