<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Proyecto de vida
    
    .titulo-segundo.mt-5.color-acento-contenido
      #t_4_1.h2 4.1 Estudio del sector o de la industria
    separador 
    
    .titulo-segundo.mt-5.color-acento-contenido
      #t_4_2.h2 4.2 Estructura del proyecto de vida

</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
