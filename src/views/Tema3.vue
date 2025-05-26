<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Relación entre la anatomía del calzado y el pie

    p.mb-4 El calzado debe adaptarse a la estructura del pie para evitar molestias o problemas de salud. Para ello, es fundamental considerar:

    .row.mb-5
      .col-sm-6.col-lg-4.mb-4.mb-lg-0(data-aos="zoom-in")
        .tarjeta--boton.color-primario.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src="@/assets/curso/temas/img39.svg", alt="" style="max-width: 100px").m-auto
          h3.text-center Forma del pie
          p.mb-0 Existen diferentes tipos de arcos (alto, medio y plano) que influyen en la elección del calzado.
      .col-sm-6.col-lg-4.mb-4.mb-lg-0(data-aos="zoom-in")
        .tarjeta--boton.color-primario.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src="@/assets/curso/temas/img40.svg", alt="" style="max-width: 100px").m-auto
          h3.text-center Movilidad y presión
          p.mb-0 El diseño de la suela y la entresuela debe distribuir la presión de manera uniforme.
      .col-sm-6.col-lg-4.mb-4.mb-sm-0(data-aos="zoom-in")
        .tarjeta--boton.color-primario.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src="@/assets/curso/temas/img41.svg", alt="" style="max-width: 100px").m-auto
          h3.text-center Tamaño y ajuste
          p.mb-0 Un calzado inadecuado puede generar ampollas, juanetes o fatiga muscular.

    .fondo___color.ajustes___movil-2
      .px-5
        p.mb-4 El estudio detallado de la anatomía del calzado es clave para la fabricación de productos que brinden comodidad, seguridad y funcionalidad, adaptándose a las necesidades del usuario, es por ello que es importante reconocer la estructura básica del pie.

        figure.mb-5(data-aos="fade-up")
          img(src="@/assets/curso/temas/img43.svg", alt="" style="max-width: 600px").m-auto

        .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
          .col-lg-auto
            figure
              img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
          .col
            h3 Clasificación según la forma del pie
        
        p.mb-4.ajustes___movil-1 Los pies presentan variaciones en su forma y estructura, lo que permite clasificarlos según distintos criterios. Uno de los más utilizados es la longitud de los dedos, ya que influye en la distribución del peso y la estabilidad al caminar. A continuación, se describen las principales tipologías de pies según su forma.
    
        figure.mb-5(data-aos="fade-up")
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/UPDQ7P_fhlU" title="Clasificación según forma del pie" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Clasificación según el tipo de arco plantar

    p.mb-4.ajustes___movil-1 El arco plantar es la curvatura ubicada en la parte interna del pie y desempeña un papel clave en la distribución del peso y la absorción del impacto al caminar o correr.

    TabsC.color-acento-contenido.mb-5(data-aos="zoom-in")

      .py-3.py-md-4(titulo="Pie normal o arco medio")
        .row.justify-content-center.align-items-center
          .col-xl-5.order-2.order-lg-1
            figure.d-none.d-xl-block
              img(src='@/assets/curso/temas/img44.svg', alt="" style="max-width: 300px").m-auto
          .col-xl-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura.mb-4 Pie normal o arco medio
            p.mb-0 Presenta una curvatura moderada. Distribuye bien el peso y la presión al caminar.

      .py-3.py-md-4(titulo="Pie plano (arco bajo)")
        .row.justify-content-center.align-items-center
          .col-xl-5.order-2.order-lg-1
            figure.d-none.d-xl-block
              img(src='@/assets/curso/temas/img45.svg', alt="" style="max-width: 300px").m-auto
          .col-xl-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura.mb-4 Pie plano (arco bajo)
            p.mb-0 La curvatura es mínima o inexistente, haciendo que casi toda la planta toque el suelo. Puede generar problemas de postura y dolor en pies o rodillas.

      .py-3.py-md-4(titulo="Pie cavo (arco alto)")
        .row.justify-content-center.align-items-center
          .col-xl-5.order-2.order-lg-1
            figure.d-none.d-xl-block
              img(src='@/assets/curso/temas/img46.svg', alt="" style="max-width: 300px").m-auto
          .col-xl-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura.mb-4 Pie cavo (arco alto)
            p.mb-0 El arco es muy pronunciado, dejando un espacio elevado entre la planta y el suelo. Puede causar mayor presión en el talón y metatarso, generando dolor o problemas de estabilidad.
      
      .py-3.py-md-4(titulo="<em>Hallux Valgus</em> (Juanete)")
        .row.justify-content-center.align-items-center
          .col-xl-5.order-2.order-lg-1
            figure.d-none.d-xl-block
              img(src='@/assets/curso/temas/img47.svg', alt="" style="max-width: 300px").m-auto
          .col-xl-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura.mb-4 <em>Hallux Valgus</em> (Juanete)
            p.mb-0 El dedo gordo se inclina hacia el segundo dedo, formando una protuberancia ósea en la base del dedo. Puede causar dolor, inflamación y enrojecimiento. También puede derivar en deformidades como dedos en garra o superposición de dedos.
            
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Clasificación según la pisada

    p.mb-4.ajustes___movil-1 La pisada se define por la forma en que el pie entra en contacto con el suelo al caminar o correr, influyendo en la estabilidad y distribución del peso.

    .row.justify-content-center
      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/img48.svg", alt="alt")
          .crd_hover_txt--body
            h4.mb-3 Pisada neutra
            p.mb-0 El peso se distribuye de manera equilibrada desde el talón hasta los dedos. Es la más eficiente y saludable.

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/img49.svg", alt="alt")
          .crd_hover_txt--body
            h4.mb-3 Pisada pronadora
            p.mb-0 El pie tiende a inclinarse hacia adentro al caminar. Es común en personas con pie plano y puede causar desgaste excesivo en la parte interna del calzado.

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/img50.svg", alt="alt")
          .crd_hover_txt--body
            h4.mb-3 Pisada supinadora
            p.mb-0 El pie se inclina hacia afuera al caminar. Es más frecuente en personas con pie cavo y puede generar problemas en tobillos y rodillas.

</template>

<script>
export default {
  name: 'Tema3',
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
