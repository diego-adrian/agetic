<template>
  <section class="navbar">
    <div class="ladoDerecho">
      BOLIVIA A TU SERVICIO
    </div>
    <div class="ladoIzquierdo">
      <ul>
        <li>Ciudadania</li>
        <li>Gobierno</li>
        <li>Prensa</li>
        <li>Transparencia</li>
        <li>&nbsp;&nbsp;</li>
        <li>&nbsp;</li>
      </ul>
    </div>
  </section>
</template>
<script>
export default {
  data () {
  }
};
</script>
<style lang="scss" scoped>
  @import '../../assets/scss/variables.scss';
  .navbar {
    position: absolute;
    top: 0;
    right: 0;
    left: 0;
    color: #FFF;
    z-index: 1;
    width: 100%;
    border-bottom: 2px solid #FFF;
    font-size: 1vw;
    .ladoDerecho {
      left: 0;
      padding: 12px 25px;
      float: left;
    }
    .ladoIzquierdo {
      ul {
        right: 0;
        float: right;
        list-style: none;
        li {
          cursor: pointer;
          display: inline;
          padding: 12px 25px;
          border-left: 2px solid #FFF;
        }
      }
    }
  }
</style>

