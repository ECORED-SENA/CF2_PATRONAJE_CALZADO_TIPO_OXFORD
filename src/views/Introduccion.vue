<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p.mb-5 El patronaje de calzado es un proceso técnico y creativo que transforma una idea de diseño en piezas concretas para su producción. A través del estudio de materiales, sistemas de medidas y estructuras como las hormas, se logra una representación precisa que garantiza la comodidad, funcionalidad y estética del calzado.

    .fondo_img.ajustes___movil-1
      .px-5
        .row.align-items-center
          .col-xl
            .row.align-items-center.mb-3.caja-text-intro(data-aos="fade-right")
              .col-xl-auto
                figure.d-none.d-xl-block
                  img(src="@/assets/curso/intro/img1.png", alt="" style="max-width: 350px").m-auto
              .col-xl
                p.mb-0 En el caso específico de los modelos Oxford, este proceso adquiere relevancia por sus características formales y estructurales, las cuales exigen un alto nivel de precisión en el diseño y corte. Comprender los diferentes tipos de materiales, como cueros, sintéticos y textiles, permite tomar decisiones adecuadas que influyen en la durabilidad y el estilo del producto final.
            p.mb-3 Este componente formativo brinda las bases fundamentales para conocer la anatomía del calzado, la clasificación de hormas y la elaboración de moldes. El dominio de estos elementos es esencial para asegurar un calzado bien estructurado, adaptado al pie y con una calidad técnica que responda a las exigencias del mercado.
          .col-xl-auto
            figure(data-aos="fade-left").d-none.d-xl-block
              img(src="@/assets/curso/intro/img3.png", alt="" style="max-width: 280px").m-auto

</template>

<script>
export default {
  name: 'Introduccion',
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
