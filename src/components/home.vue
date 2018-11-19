<template>
  <section class="home">
    <div class="imagenFondo"></div>
    <div class="fondoAzul"></div>
    <div class="descripcionHome">
      <span>Estado Plurinacional de Bolivia</span>
      <span>Ministerio de Obras Publicas</span>
      <span>Servicios y Vivienda</span>
    </div>
  </section>
</template>
<script>
export default {
  data () {
    return {};
  }
};
</script>
<style lang="scss" scoped>
  @import '../assets/scss/variables.scss';
  .home {
    .imagenFondo {
      position: fixed;
      left: 0;
      top: 0;
      right: 0;
      bottom: 0;
      background-image: url('../../static/images/background.jpg');
      background-size: cover;
      background-repeat: no-repeat;
    }
    .fondoAzul {
      background: rgba($color: darken($azul, 30), $alpha: .5);
      position: fixed;
      top: 0;
      bottom: 0;
      left: 0;
      right: 0;
    }
    .contenidoPrincipal {
      position: absolute;
      top: 0;
      left: 0;
      color: #FFF;
    }
    .descripcionHome {
      position: absolute;
      top: 15%;
      left: 10%;
      border-left: 2px solid #FFF;
      color: #FFF;
      span {
        padding-left: 10px;
        display: block;
        text-align: left;
        &:first {
          font-size: 1.2vw;
        }
      }
    }
  }
</style>
