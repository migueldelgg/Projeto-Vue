<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>
  
<script>
import burgerImage from '../../public/img/burger.jpg';

export default {
  name: 'Banner',
  data() {
    return {
      burgerImage,
    };
  },
};
</script>

<style scoped>

    #main-banner {
        background-image: url('/public/img/burger.jpg');
        background-position: 0 -200px; /* Ajuste o valor para mover a imagem para cima */
        background-size: cover;
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1 {
        color: #fff;
        text-align: center;
        font-size: 60px;
        background-color: #222;
        padding: 20px 40px;
    }


</style>