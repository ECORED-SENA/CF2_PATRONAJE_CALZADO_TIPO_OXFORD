<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Herramientas utilizadas en el proceso de patronaje

    .row.align-items-center.mb-5
      .col-xl
        p.mb-0 Antes de iniciar el proceso de enmascarado, es fundamental realizar el alistamiento de las herramientas necesarias para llevar a cabo esta actividad de manera eficiente. A continuación, se presentan las herramientas requeridas.
      .col-xl-auto
        figure(data-aos="fade-left").d-none.d-xl-block
          img(src="@/assets/curso/temas/img51.svg", alt="" style="max-width: 295px").m-auto
    
    .estilo___caja_19.m-0
      figure.mb-5(data-aos="zoom-in")
        img(src='@/assets/curso/temas/img52.png', alt='Herramientas sobre una mesa , incluyendo cuchilla, borrador, compás, reglas, tijeras, cinta, portaminas, piedra de afilar y tabla de corte.' style="max-width: 500px").m-auto
      .row.justify-content-center
        .col-xl-10
          .row.align-items-center.fondo___img_3(data-aos="zoom-in")
            .col-xl-7
              ol.lista-ol
                li 
                  span.text-bold A. 
                  | Cuchilla de corte.
              ol.lista-ol
                li 
                  span.text-bold B. 
                  | Borrador.
              ol.lista-ol
                li 
                  span.text-bold C. 
                  | Compás de puntas secas o compás de precisión.
              ol.lista-ol
                li 
                  span.text-bold D. 
                  | Regla metálica de 15 cm.
              ol.lista-ol
                li 
                  span.text-bold E. 
                  | Portaminas.
              ol.lista-ol
                li 
                  span.text-bold F. 
                  | Tijeras.
              ol.lista-ol
                li 
                  span.text-bold G. 
                  | Cinta de enmascarar.
              ol.lista-ol
                li 
                  span.text-bold H. 
                  | Piedra de afilar.
              ol.lista-ol
                li 
                  span.text-bold I. 
                  | Regla metálica de 30 cm.
              ol.lista-ol
                li 
                  span.text-bold J. 
                  | Metro de calzado o cinta métrica.
              ol.lista-ol
                li 
                  span.text-bold K. 
                  | Tabla de corte.
            .col-xl-5
              figure(data-aos="fade-left").d-none.d-xl-block
                img.ajuste___width_img(src="@/assets/curso/temas/img76.svg", alt="" ).m-auto

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
