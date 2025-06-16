<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.align-items-center.mb-5
      .col-xl
        p.mb-0 El desarrollo técnico del calzado requiere comprender a fondo las estructuras que intervienen en su diseño, especialmente cuando se trata de modelos con características clásicas y específicas como el Oxford. Este tipo de calzado se distingue por su formalidad, costuras definidas y una construcción que exige precisión para lograr un ajuste cómodo y una apariencia refinada. Por ello, el estudio del patronaje aplicado al modelo Oxford se convierte en una herramienta clave para asegurar su correcta fabricación.
      .col-xl-auto
        figure.d-none.d-xl-block(data-aos="fade-left")
          img(src="@/assets/curso/intro/img4.png", alt="" style="max-width: 350px").m-auto

    

    .fondo_img.ajustes___movil-1
      .px-5
        .row.align-items-center
          .col-xl-auto
            figure(data-aos="fade-right").d-none.d-xl-block
              img(src="@/assets/curso/intro/img3.png", alt="" style="max-width: 280px").m-auto
          .col-xl
            .row.align-items-center.mb-3.caja-text-intro(data-aos="fade-left")
              .col-xl-auto
                figure.d-none.d-xl-block
                  img(src="@/assets/curso/intro/img1.jpg", alt="" style="max-width: 350px").m-auto
              .col-xl
                p.mb-0 Este componente formativo proporciona los fundamentos necesarios para analizar las medidas del pie, identificar las partes de la horma y relacionar la anatomía del calzado con la estructura del pie humano. En este contexto, se abordan también las herramientas propias del patronaje y las técnicas de enmascarado como pasos esenciales para obtener moldes que permitan replicar de manera fiel el diseño del calzado Oxford. Este proceso garantiza que las piezas cortadas se adapten correctamente a la forma del pie y a las exigencias del diseño.
            p.mb-0.caja-text-intro_1(data-aos="fade-left") A lo largo del contenido, se orienta al aprendiz en la comprensión de las proporciones, el volumen y las características técnicas que definen una horma adecuada para este tipo de calzado. Así, se fortalece la capacidad de tomar decisiones informadas sobre materiales, medidas y formas, lo cual resulta indispensable para alcanzar productos con calidad, confort y una presentación que responda tanto a criterios funcionales como estéticos.
          
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
