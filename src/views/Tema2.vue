<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Hormas

    <!-- BLOQUE 0 -->
    .row.align-items-center.mb-5.estilo___caja_20.ajuste___color_1(data-aos="fade-up")
      .col-xl-auto
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img15.png", alt="" style="max-width: 500px").m-auto
      .col-xl
        p.mb-0 Cuando hablamos de “horma”, nos referimos a un molde con la forma estilizada del pie humano cuya función principal es servir de referencia y soporte durante la construcción del calzado. Las hormas definen la forma, volumen, curva y silueta del zapato, convirtiéndose en una herramienta fundamental en todo proceso de fabricación.

    <!-- BLOQUE  -->
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 Partes de la horma
    
    .row.mb-5.align-items-center.ajustes___movil-1(data-aos="fade-right")
      .col-xl-6.estilo___caja-tema4
        .row.align-items-center.mb-3
          .col-xl-auto
            figure.d-none.d-xl-block(data-aos="fade-right")
              img(src="@/assets/curso/temas/img69.svg", alt="" style="max-width: 90px").m-auto 
          .col-xl
            p.mb-0 Aunque pueda parecer una estructura simple, la horma está compuesta por múltiples partes, cada una con una función técnica específica. A continuación, se describen las partes principales que pueden variar según el tipo de horma:
        <ul class="fa-ul">
          <li class="mb-4"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Lado medial</strong>: corresponde a la parte interior del pie. Es donde se ubican el dedo gordo y el arco plantar.</li>
          <li class="mb-0"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Lado lateral</strong>: se refiere al lado externo del pie, donde se encuentra el dedo meñique.</li>
        </ul>
      .col-xl-6(data-aos="fade-left").ajustes___movil-3
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 2. 
          span Vista inferior de la horma con línea de referencia del punto de quiebre
        figure.mb-1(data-aos="zoom-in")
          img(src="@/assets/curso/temas/img16.png", alt="Vista lateral superior de una horma de calzado de madera con una línea roja horizontal que atraviesa el centro, marcando la alineación longitudinal de la horma. ").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Zonas estructurales de la horma

    .row.mb-5.align-items-center.m-0
      .col-xl-6(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 3. 
          span Vista lateral de la horma con línea del frente del tacón
        figure.mb-1(data-aos="zoom-in")
          img(src="@/assets/curso/temas/img17.png", alt="Vista lateral de una horma de calzado de madera con una línea vertical roja que indica la ubicación del punto de apoyo más alto del empeine.").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
      .col-xl-6.estilo___caja-tema4-1.ajustes___movil-3(data-aos="fade-left")
        .row.align-items-center.mb-5
          .col-xl-auto
            figure.d-none.d-xl-block(data-aos="fade-right")
              img(src="@/assets/curso/temas/img70.svg", alt="" style="max-width: 90px").m-auto 
          .col-xl
            p.mb-0 Estas secciones definen el diseño anatómico básico de la horma:
        <ul class="fa-ul">
          <li class="mb-4"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Parte delantera</strong>: inicia a partir de la línea de perímetro de la bola del pie o zona de articulación (metatarsos).</li>
          <li class="mb-0"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Parte trasera</strong>: comprende desde la línea de articulación hasta el extremo del talón.</li>
        </ul>
      
    p.mb-5.ajustes___movil-1 A continuación se presentan los elementos más representativos de una horma, los cuales cumplen funciones específicas en el proceso de fabricación del calzado:

    .row.align-items-center.mb-5
      .col-xl-6
        .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade-right")
          h5 Figura 4. 
          span Vista superior de la horma con partes funcionales señaladas
        figure.mb-1(data-aos="zoom-in")
          img(src="@/assets/curso/temas/img18.png", alt="Vista superior de una horma de calzado de madera con etiquetas que señalan partes clave: cono (zona delantera), bisagra (unión móvil), apertura (ranura central), talla (marca de medida), tubo (perforación central) y mesa (base trasera).").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
      .col-xl-6(data-aos="fade-left").ajustes___movil-3
        LineaTiempoD.color-secundario
          p(numero="1" titulo="Cono") Comienza en la parte más alta y se extiende hasta el empeine, coincidiendo con el punto más prominente del pie.

          p(numero="2" titulo="Bisagra") Pieza funcional que permite abrir o articular la horma.

          p(numero="3" titulo="Apertura") Sección recortada de la horma que incorpora la bisagra. Tiene cara delantera y trasera. No todas las hormas incluyen este mecanismo.

          p(numero="4" titulo="Talla") Número o referencia grabada en la horma. Debe ser legible incluso con el corte montado.

          p(numero="5" titulo="Tubo") Orificio ubicado en la parte superior de la horma, con medidas estándar de 10,5 mm de diámetro y 38 mm de profundidad. Sirve para fijar la horma en equipos o estanterías.

          p(numero="6" titulo="Mesa") Superficie plana donde se localizan tanto el tubo como la talla.

    .row.align-items-center.mb-5.ajustes___movil-2.m-0
      .col-xl-6.estilo___caja-tema4-2(data-aos="fade-right")
        .row.align-items-center.mb-4
          .col-xl-auto
            figure.d-none.d-xl-block(data-aos="fade-right")
              img(src="@/assets/curso/temas/img71.svg", alt="" style="max-width: 90px").m-auto 
          .col-xl
            p.mb-4.ajustes___movil-1 Además de las partes principales, existen componentes que cumplen funciones específicas en el diseño y la funcionalidad de la horma:
        <ul class="fa-ul">
          <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Perfil de la puntera</strong>: superficie curva que va desde el empeine hasta el canto a la altura del dedo gordo.</li>
          <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Talón (cuboide)</strong>: zona más ancha de la parte posterior de la horma, ubicada por encima del canto.</li>
          <li class="mb-0"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Orificios</strong>: ubicados en los laterales, permiten fijar piezas metálicas que sujetan la bisagra.</li>
        </ul>
      .col-xl-6(data-aos="fade-left").ajustes___movil-3
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 5. 
          span Perfil lateral de la horma con elementos constructivos
        figure.mb-1.estilo___caja_img(data-aos="zoom-in")
          img(src="@/assets/curso/temas/img19.png", alt="Vista lateral de una horma de madera que destaca elementos estructurales clave: perfil de la puntera, cono, orificios, apertura y talón. ").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).

    p.mb-4.ajustes___movil-1 Estos elementos aportan soporte, protección y facilitan el proceso de fabricación del calzado:


    .row.align-items-center.mb-5
      .col-xl-6
        .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade-right")
          h5 Figura 6. 
          span Vista inferior de horma con componentes de montaje
        figure.mb-1.estilo___caja_img(data-aos="zoom-in")
          img(src="@/assets/curso/temas/img20.png", alt="Vista inferior de una horma antigua de madera donde se identifican elementos funcionales del montaje: placa para montar, canto, enfranque, agujero para tachuelas o clavos y taco." style="width: 400px").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
      .col-xl-6(data-aos="fade-left").ajustes___movil-3
        LineaTiempoD.color-secundario
          p(numero="1" titulo="Placa para montar") Lámina metálica ubicada en la parte inferior para proteger la horma. Puede cubrir puntera, talón o toda la base. Se encuentra en hormas de madera y plástico.

          p(numero="2" titulo="Canto (o dima)") Es la esquina donde se unen la pared y la planta de la horma. Puede ser redondeado o tener un ángulo de 90°.

          p(numero="3" titulo="Enfranque") Parte inferior media de la horma, entre el talón y la parte delantera.

          p(numero="4" titulo="Agujero para tachuelas o clavos") Orificio en la placa que permite fijar temporalmente piezas como la palmilla.

          p(numero="5" titulo="Taco") Inserto de caucho o plástico flexible ubicado en el agujero de tachuela, que reemplaza material más duro para permitir clavado o grapas.

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Horma de tacón alto
    
    p.mb-5.ajustes___movil-1 Aunque las hormas para calzado de mujer comparten los mismos componentes básicos, sus proporciones y diseño varían significativamente en comparación con las hormas masculinas. Algunas partes específicas de este tipo de hormas son:

    .row.align-items-center.mb-5
      .col-xl-6(data-aos="fade-right")
        LineaTiempoD.color-secundario
          p(numero="1" titulo="Punto de quiebre") Ubicado en la parte inferior de la horma, justo debajo de la línea del perímetro de articulación. Marca la división entre la parte delantera y el enfranque.

          p(numero="2" titulo="Enfranque") Zona central de la parte inferior de la horma, ubicada entre la delantera y la talonera.

          p(numero="3" titulo="Ángulo del asiento del talón") Cambia según la altura del tacón. Un tacón de 1 cm tiene un ángulo de 0º; uno de 1,3 cm tiene 1º, y este aumenta 1º por cada 3 mm. Por ejemplo, un tacón de 5 cm genera un ángulo de 16º; uno de 6,35 cm (2.5") llega a 27º.

          p(numero="4" titulo="Curvatura del talón") Radio de la curvatura del contorno de la talonera. En hormas femeninas suele ser de 90 mm; en masculinas, entre 105 mm y 115 mm.
      .col-xl-6.ajustes___movil
        .titulo-sexto.color-acento-contenido.mb-3
            h5 Figura 7. 
            span Zonas técnicas de inclinación y soporte de la horma
        figure.mb-1(data-aos="zoom-in")
          img(src="@/assets/curso/temas/img21.png", alt="Imagen lateral de una horma verde que identifica partes esenciales: cono, punto de quiebre, enfranque, ángulo del asiento del talón y curva del talón.").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
        

    p.mb-5.ajustes___movil-1 Estos elementos permiten identificar límites, zonas de contacto y proporciones clave en la estructura de la horma:

    .row.align-items-center
      .col-xl-6
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 8. 
          span Referencias geométricas principales en la base de la horma
        figure.mb-1(data-aos="zoom-in")
          img(src="@/assets/curso/temas/img22.png", alt="Vista inferior de una horma verde donde se señalan referencias clave para el diseño del calzado: puntera, delantera, punto y línea de enfranque, línea del frente del tacón, canto plano del tacón y talonera. ").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
      .col-xl-6(data-aos="fade-left").ajustes___movil-3
        LineaTiempoD.color-secundario
          p(numero="1" titulo="Puntera") Punta visible en el borde o canto de la horma.

          p(numero="2" titulo="Delantera") Parte de la horma que precede la zona de contacto con el suelo.

          p(numero="3" titulo="Línea de enfraque") Punto donde el enfranque comienza a elevarse del suelo.

          p(numero="4" titulo="Línea del frente del tacón") Se ubica a un 25 % de la longitud total de la horma, desde la parte trasera.

          p(numero="5" titulo="Canto del plano del tacón") Línea inferior que divide la talonera del enfranque.

          p(numero="6" titulo="Talonera (asiento del tacón)") Zona plana en la parte posterior inferior donde reposa el talón.

    Separador
    <!-- BLOQUE 2 -->
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.2 Dimensiones de la horma

    .row.align-items-center.mb-5
      .col-xl
        p.mb-4 La horma tiene una silueta tridimensional compleja. Para fabricarla correctamente, es necesario seguir normas específicas y realizar mediciones precisas. Conocer las dimensiones de la horma permite comunicar cambios técnicos, identificar errores estructurales y garantizar un calce adecuado. Las dimensiones estándar se dividen en medidas de longitud, ancho, circunferencia y volumen.
        .row.align-items-center.estilo___caja-tema4-3(data-aos="fade-right")
          .col-xl-auto
            figure.d-none.d-xl-block
              img(src="@/assets/curso/temas/img23.svg", alt="" style="max-width: 90px").m-auto
          .col-xl
            p.mb-0 En la zapatería comercial, se usan principalmente largo y ancho para establecer la talla. Sin embargo, en el diseño a medida y el desarrollo técnico de calzado, se requieren mediciones más detalladas y especializadas.
      .col-xl-auto(data-aos="fade-left")
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img24.png", alt="" style="max-width: 500px").m-auto

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Medidas longitudinales

    p.mb-4.ajustes___movil-1 Estas medidas determinan el largo total y parcial de la horma, base para desarrollar patrones y definir la talla del calzado.

    .fondo___img_2.mb-5
      .px-5
        .row.align-items-center
          .col-xl-4(data-aos="fade-right")
            figure.d-none.d-xl-block
              img(src='@/assets/curso/temas/img72.png', alt='' ).m-auto
          .col-xl-8(data-aos="fade-left")
            SlyderF(columnas="col-lg-6 col-xl-6")
              .tarjeta.color-acento-botones.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/curso/temas/img25.svg' style="max-width: 90px").m-auto
                h4.mb-3.estilo-text Largo de horma
                p.mb-0 También llamado longitud de calce o S.S.L en inglés. Se mide desde la talonera hasta la punta con una cinta métrica sobre la superficie.
              .tarjeta.color-acento-botones.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/curso/temas/img25.svg' style="max-width: 90px").m-auto
                h4.mb-3.estilo-text Longitud de calce
                p.mb-0 Se mide desde la puntera hasta la curva del talón, como si dos planos verticales tocaran ambos extremos mientras la horma está apoyada en una superficie plana.
              .tarjeta.color-acento-botones.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/curso/temas/img25.svg' style="max-width: 90px").m-auto
                h4.mb-3.estilo-text Longitud plantar
                p.mb-0 Medida entre los extremos inferiores de la horma, siguiendo el eje principal.
              .tarjeta.color-acento-botones.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/curso/temas/img25.svg' style="max-width: 90px").m-auto
                h4.mb-3.estilo-text Longitud de mesa
                p.mb-0 Se mide desde el borde frontal hasta la parte trasera de la superficie plana superior de la horma (mesa).

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Medidas de circunferencia y volumen

    p.mb-4.ajustes___movil-1 Estas dimensiones son esenciales para determinar el volumen interno del calzado y permiten ajustar el diseño a las características del pie humano.


    .row.align-items-center.mb-5
      .col-xl-6
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 8. 
          span Referencias geométricas principales en la base de la horma
        figure.mb-1(data-aos="zoom-in")
          img(src="@/assets/curso/temas/img26.png", alt="Imagen lateral de una horma verde con cintas amarillas marcando tres medidas clave: perímetro de la bola, perímetro de retención, perímetro de empeine y longitud de la horma.").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
      .col-xl-6(data-aos="fade-left").ajustes___movil-3
        LineaTiempoD.color-secundario
          p(numero="1" titulo="Perímetro de la bola") También llamado perímetro de articulación. Se mide alrededor de la parte más ancha del antepié, conectando los puntos de la bola medial, la bola lateral y el punto de bridaje. Este punto se encuentra al 65 % de la longitud plantar.

          p(numero="2" titulo="Perímetro de retención") Se mide desde el punto medio entre el perímetro de articulación y el perímetro de empeine hasta la mitad del cono. Se toma a 25 mm desde el punto de bridaje en el cono y 25 mm desde la línea de ancho de bola en la planta.

          p(numero="3" titulo="Perímetro de empeine") Se mide desde el enfranque hasta la parte superior del cono. Se toma 25 mm por encima del perímetro de retención, y 25 mm por detrás de este en la planta.

          p(numero="4" titulo="Perímetro talón-cuñas") Medición que va desde el canto del talón, pasando por el cuboide, hasta el cruce del perímetro del empeine con el eje principal. Determina el tamaño de la abertura del zapato. En un zapato sin cordones talla 9 US de hombre, puede variar entre 360 mm y 378 mm.

          p(numero="5" titulo="Perímetro talonera-empeine") También llamado perímetro de entrada. Se mide desde el punto del talón, pasando por el cuboide, hasta el punto de bridaje sobre el eje principal.

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Medidas verticales y de apoyo

    .row.align-items-center.mb-5.ajustes___movil-1.m-0
      .col-xl-6.estilo___caja-tema4-2(data-aos="fade-up")
        p.mb-5 Estas medidas determinan la altura, elevación y perfil del zapato.
        <ul class="fa-ul">
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Altura de la puntera</strong>: volumen de la horma en la zona del dedo gordo.</li>
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Salida o quebrante de la punta</strong>: se refiere a la distancia entre el plano del suelo y el extremo de la puntera. Puede ser inexistente en zapatillas planas o superior a 10 mm en botas de senderismo.</li>
          <li class="mb-0"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Altura de tacón</strong>: distancia entre la talonera y el suelo. Varía desde 0 mm en calzado plano hasta 100 mm o más en tacones altos.</li>
        </ul>
      .col-xl-6(data-aos="fade-left").ajustes___movil-3
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 10. 
          span Medidas verticales y de perímetro desde vista lateral
        figure(data-aos="fade-left")
          img(src="@/assets/curso/temas/img27.png", alt="Imagen lateral de una horma verde que presenta medidas clave para el diseño de calzado: perímetro talón-empeine, perímetro talón-cuello, altura del tacón, longitud de calce, salida y altura de la puntera. ").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Medidas de ancho y base

    p.mb-4.ajustes___movil-1 Estas dimensiones establecen el soporte y la base del calzado, fundamentales para la estabilidad y confort.

    .row.align-items-center.mb-5
      .col-xl-6(data-aos="fade-right").d-none.d-xl-block
        figure
          img(src="@/assets/curso/temas/img28.png", alt="").m-auto
      .col-xl-6(data-aos="fade-left")
        LineaTiempoD.color-secundario
          p(numero="1" titulo="Ancho de flancos") Se mide transversalmente en la parte delantera de la horma, uniendo el punto de la bola medial con el de la bola lateral.

          p(numero="2" titulo="Anchura plantar") Se mide en la planta de la horma, 25 mm detrás del ancho de la bola.

          p(numero="3" titulo="Anchura de la cintura") Se toma 25 mm detrás de la anchura plantar, en la parte media inferior de la horma.

          p(numero="4" titulo="Anchura del talón") Se mide en la base trasera, justo por delante de la talonera, a una distancia del 25 % de la longitud plantar.

          p(numero="5" titulo="Ancho de talón (cuboides)") Corresponde al punto más ancho de la parte trasera de la horma.

          p(numero="6" titulo="Ancho de mesa") Se toma transversalmente en la parte superior de la horma, sobre la placa superior, desde el lado medial hasta el lateral.

    .titulo-sexto.color-acento-contenido.mb-3.ajustes___movil-1(data-aos="fade-right")
      h5 Figura 11. 
      span Vista posterior y superior de la horma con medidas clave

    figure.estilo___caja_3.mb-1(data-aos="fade-up")
      img(src="@/assets/curso/temas/img29.png", alt="Vista inferior y frontal de una horma verde que ilustra las principales medidas plantares utilizadas en el diseño de calzado: longitud plantar, ancho de flancos, anchura plantar, anchura de la cintura y anchura del talón. " style="width: 500px").m-auto
    figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).

    Separador
    <!-- BLOQUE  -->
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.3 Clasificación de las hormas

    p.mb-5.ajustes___movil-1 Las hormas se pueden clasificar de diversas maneras, según el usuario, la tipología del calzado, el sistema de extracción y la altura del tacón. Estas clasificaciones permiten seleccionar la horma adecuada de acuerdo con la funcionalidad, el diseño y las necesidades específicas de cada calzado.

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Según el usuario

    p.mb-4.ajustes___movil-1 Esta clasificación considera las características fisiológicas y las necesidades particulares del usuario.

    .fondo___slider.mb-5
      .px-5
        .ajuste-slider(data-aos="zoom-in")
          SlyderA(tipo="b")
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img30.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6.mb-4
                h4.txt--purpura.mb-4 Según el género y la edad
                <ul class="fa-ul">
                  <li class="mb-3"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Horma para dama</strong>: con formas más estilizadas, menor volumen en el empeine y el talón.</li>
                  <li class="mb-3"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Horma para caballero</strong>: más ancha y robusta, con mayor soporte en la planta del pie.</li>
                  <li class="mb-0"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Horma infantil</strong>: adaptada a pies en crecimiento, flexible y con refuerzo en el arco.</li>
                </ul>
              
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img31.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6.mb-4
                h4.txt--purpura.mb-4 Según el tipo de pie
                <ul class="fa-ul">
                  <li class="mb-3"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Horma estándar (normal)</strong>: para pies con proporciones promedio; utilizada en calzado convencional.</li>
                  <li class="mb-3"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Horma para pie ancho</strong>: con mayor espacio en la parte delantera y lateral, ideal para pies voluminosos.</li>
                  <li class="mb-3"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Horma para pie delgado</strong>: más ajustada en metatarso y talón, evita deslizamientos dentro del zapato.</li>
                  <li class="mb-0"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Horma ortopédica</strong>: proporciona soporte específico en el arco, estabilidad y comodidad para pies con requerimientos especiales.</li>
                </ul>

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img32.png', alt='' style="max-width: 500px").m-auto
              .col-xl-6.mb-4
                h4.txt--purpura.mb-4 Según la aplicación o uso
                <ul class="fa-ul">
                  <li class="mb-3"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Horma deportiva</strong>: optimizada para rendimiento, con buena flexibilidad y soporte.</li>
                  <li class="mb-3"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Horma de seguridad</strong>: más ancha, resistente, y con espacio para punteras protectoras.</li>
                  <li class="mb-3"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Horma de moda</strong>: estilizada, con formas innovadoras centradas en la estética.</li>
                  <li class="mb-0"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Horma confort</strong>: diseñada para uso prolongado, con materiales acolchados y mayor espacio interior.</li>
                </ul>

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Según la familia de calzado a la que pertenezca

    .row.mb-5.align-items-center.ajustes___movil-1(data-aos="fade-up")
      .col-xl.estilo___caja-tema4-6
        p.mb-3 Las hormas varían según el tipo de zapato que se desea fabricar. Algunas de las más comunes incluyen:
        <ul class="fa-ul">
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Tubular.</strong></li>
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Mocasín.</strong></li>
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Calzado de dama clásico (con diferentes alturas de tacón).</strong></li>
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Calzado de hombre clásico.</strong></li>
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Deportivos.</strong></li>
          <li class="mb-0"><span class="fa-li"><i class="fas fa-cut color___ul_1"></i></span><strong>Botas y botines.</strong></li>
        </ul>
      .col-xl-auto
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img33.png" style="max-width: 550px")
        
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Según el sistema de extracción

    p.mb-5.ajustes___movil-1 Esta clasificación se refiere al mecanismo que permite retirar la horma del interior del calzado durante la fabricación:

    TabsA.color-acento-contenido.mb-5(data-aos="zoom-in")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Horma entera")
        .row.align-items-center
          .col-lg
            h4 Horma entera
            p.mb-0 Horma completa sin divisiones ni mecanismos. Usada en sandalias, zapatos de salón y zapatos con diseño abierto que permiten deshormado sin dificultad.
          .col-lg-auto
            figure.d-none.d-xl-block
              img(src="@/assets/curso/temas/img34.png", alt="" style="max-width: 350px").m-auto
      .tarjeta.color-acento-botones--borde.p-4(titulo="Horma con cuña")
        .row.align-items-center
          .col-lg
            h4 Horma con cuña
            p.mb-0 Incorpora una pieza divisible en la zona del empeine que se separa para facilitar el deshormado. Indicada para zapatos abotinados o botines. Muy utilizada en botas y zapatos abotinados.
          .col-lg-auto
            figure.d-none.d-xl-block
              img(src="@/assets/curso/temas/img35.png", alt="" style="max-width: 350px").m-auto
      .tarjeta.color-acento-botones--borde.p-4(titulo="Horma con articulado Alfa (V)")
        .row.align-items-center
          .col-lg
            h4 Horma con articulado Alfa (V)
            p.mb-0 Tiene una bisagra que permite la reducción y apertura de la horma.
          .col-lg-auto
            figure.d-none.d-xl-block
              img(src="@/assets/curso/temas/img36.png", alt="" style="max-width: 350px").m-auto
      .tarjeta.color-acento-botones--borde.p-4(titulo="Horma con articulado Tendo (Kiowa)")
        .row.align-items-center
          .col-lg
            h4 Horma con articulado Tendo (Kiowa)
            p.mb-0 El talón se desliza hacia arriba sin torsionar el calzado. Reduce la horma durante la extracción. Ideal para calzado plano y botas de baja altura.
          .col-lg-auto
            figure.d-none.d-xl-block
              img(src="@/assets/curso/temas/img37.png", alt="" style="max-width: 350px").m-auto

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 55px").m-auto
      .col
        h3 Según la altura del tacón

    p.mb-5.ajustes___movil-1 La inclinación de la horma influye directamente en el diseño del calzado y en el tipo de soporte que brinda al pie. Se clasifica de la siguiente manera:

    .row.mb-5
      .col-xl-auto
        .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade-right")
          h5 Tabla 4. 
          span Clasificación de hormas según altura del tacón
        .tabla-a.mb-4.ajuste--text.ajuste___tabla_4(data-aos="fade-up")
          table
            thead
              tr
                th.ajuste-border-tabla Clasificación
                th.ajuste-border-tabla Altura del tacón
                th.ajuste-border-tabla Características
                th Ejemplos de calzado
            tbody
              tr.ajuste-color-tabla
                td.ajuste-border-tabla Horma plana
                td.ajuste-border-tabla 0 - 1 cm
                td.ajuste-border-tabla.texto-left Ofrece máxima estabilidad y comodidad. Ideal para uso prolongado.
                td.texto-left Zapatillas deportivas, zapatos de seguridad, sandalias planas.
              tr
                td.ajuste-border-tabla Horma baja
                td.ajuste-border-tabla 1.5 - 3.5 cm
                td.ajuste-border-tabla.texto-left Mejora la postura sin comprometer la comodidad.
                td.texto-left Mocasines, zapatos escolares, botas bajas.
              tr.ajuste-color-tabla
                td.ajuste-border-tabla Horma media
                td.ajuste-border-tabla 3.5 - 6.5 cm
                td.ajuste-border-tabla.texto-left Equilibrio entre estilo y confort. Inclinación moderada.
                td.texto-left Zapatos de oficina, botines, tacones medianos.
              tr
                td.ajuste-border-tabla Horma alta
                td.ajuste-border-tabla 6.5 - 9.5 cm
                td.ajuste-border-tabla.texto-left Estiliza la figura. Requiere materiales de soporte.
                td.texto-left Tacones de vestir, sandalias elegantes, botas altas.
              tr.ajuste-color-tabla
                td.ajuste-border-tabla Horma extra alta
                td.ajuste-border-tabla Más de 9 cm
                td.ajuste-border-tabla.texto-left Máxima inclinación. Menor comodidad para uso prolongado.
                td.texto-left <em>Stilettos</em>, plataformas, calzado de pasarela.
    
    p.mb-5.ajustes___movil-2 A medida que la talla aumenta, también lo hace la altura necesaria del tacón para mantener la misma proporción ergonómica y estética en el diseño del calzado.
    
 
    .titulo-sexto.color-acento-contenido.mb-3.ajustes___movil-1(data-aos="fade-right")
      h5 Figura 12. 
      span Relación entre la talla y la altura del tacón

    figure(data-aos="fade-right")
      img.estilo___caja_4(src="@/assets/curso/temas/img38.png", alt="Ilustración de varias hormas de calzado representadas por curvas superpuestas, cada una correspondiente a una talla distinta, desde la 1½ hasta la 8½." style="max-width: 1100px").m-auto

</template>

<script>
export default {
  name: 'Tema2',
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
