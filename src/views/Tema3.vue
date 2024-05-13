<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Evaluación financiera y social 

    .row.justify-content-center.align-items-center.mb-4
      .col-md-5.col-8.mb-md-0.mb-4
        figure.mb-5(data-aos="fade-right")
          img(src='@/assets/curso/temas/tema3/img01.png')
      .col-md-7.col-10
        p La evaluación financiera y social se basa en realizar estimaciones de lo que proyecta el futuro, los beneficios y costos asociados durante un horizonte de tiempo. Al plantearlas el analista debe conocer la actividad económica a la que se dedica la empresa, el entorno en que se desempeña la organización, así como el comportamiento de los precios, la ubicación y acceso a los insumos, prever los avances tecnológicos, la evolución de la demanda, el comportamiento de la competencia, cambios de gobierno o de política económica y social, leyes aplicables al sector y demás variables del entorno; todos ellos influyen en las alternativas planteadas por los analistas que seguramente no van a coincidir. 
        p.mb-0 Estas permiten determinar, de manera objetiva, las magnitudes numéricas de los resultados a obtener, apoyadas en cálculos matemáticos donde se validarán supuestos que han tenido origen en la realidad organizacional con el fin de tener una correcta valuación de los beneficios esperados.

    .row.justify-content-center.align-items-center.mb-4
      .col-12
        p.mb-0 Como se ha planteado en anteriores apartados de este componente, antes de embarcarse en este viaje de la evaluación financiera y social es necesario definir el objetivo de estas para tener claro el o los criterios de evaluación, anotando que ambas tienen marcadas diferencias, pero siempre tendrá mayor relevancia la alternativa que se enmarque en la realidad económica e institucional de una nación de acuerdo con las ventajas y desventajas cualitativas y cuantitativas que impliquen la designación de recursos.
      //- .col-md-7.col-10.order-md-1.order-2
      //-   .bloque-texto-b.color-acento-contenido.bloque01.p-4
      //-     .bloque-texto-b__texto(data-aos="fade-right")
      //-   p.mb-0 Como se ha planteado en anteriores apartados de este componente, antes de embarcarse en este viaje de la evaluación financiera y social es necesario definir el objetivo de estas para tener claro el o los criterios de evaluación, anotando que ambas tienen marcadas diferencias, pero siempre tendrá mayor relevancia la alternativa que se enmarque en la realidad económica e institucional de una nación de acuerdo con las ventajas y desventajas cualitativas y cuantitativas que impliquen la designación de recursos.
      //- .col-md-3.col-6.order-md-2.order-1.mb-md-0.mb-4
      //-   figure.mb-5(data-aos="fade-left")
      //-     img(src='@/assets/curso/temas/tema3/img02.png')
    
    .row.justify-content-center.align-items-center.cajon.color-primario.p-4.mb-4
      .col-md-2.col-4(data-aos="fade-right")
        img(src='@/assets/curso/temas/tema3/img03.png')
      .col-md-9.col-11
        p Para realizar la evaluación financiera y social el inversionista no acude a la información que le brinda los estados financieros de la situación financiera y de resultados que en un proyecto de inversión o una empresa en marcha serían proyecciones de las probabilidades de éxito que se podría alcanzar con x alternativa de inversión. En esta parte de la evaluación financiera y social la herramienta básica para evaluar una alternativa de inversiones el flujo de caja o de efectivo.

    p Este estado financiero conocido según las NIIF como flujo de efectivo que en síntesis es la consolidación de ingresos y egresos para que la organización pueda proyectarse acerca de los ingresos que recibirá y de los costos y gastos que deberá asumir para garantizar la operatividad de la empresa. Como complemento, observe con el siguiente video los elementos a tener presente dentro de la información financiera desde el uso de las NIF en las empresas:

    figure.mb-5(data-aos="fade-right")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/duUyd-RoZrU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    .h4.mb-4.mt-5(data-aos="zoom-down-right")
      span.titulo-herramientas Flujo de fondos, flujo de efectivo o flujo de caja libre
    
    .row.justify-content-center.align-items-center.mb-4
      .col-md-7.col-12.order-md-1.order-2.mb-md-0.mb-4
        p Este es un estado financiero de mucha importancia para la evaluación financiera de un proyecto de inversión, ya que es el instrumento que arroja la información o resultados sobre los que se determinan los beneficios a recibir por el proyecto, en los que, además de incluir ingresos y gastos, es necesario incluir la depreciación, amortización del activo nominal, valor residual, utilidades y pérdidas.
        p.mb-0 Este ejercicio tiene su grado de complejidad, ya que requiere de la elaboración de un flujo de acuerdo con su fin; es decir, un flujo de caja para medir la rentabilidad, otro para evaluar los resultados de los recursos propios y el último para definir la capacidad de pago frente a obligaciones financieras; estos también difieren si la evaluación se realiza sobre un proyecto a implementar o sobre una actividad económica en marcha.
      .col-md-5.col-8.order-md-2.order-1
        figure.mb-5(data-aos="fade-left")
          img(src='@/assets/curso/temas/tema3/img04.png')

    .row.justify-content-center.align-items-center.mb-4
      .col-md-4.col-8.mb-md-0.mb-4
        img(src='@/assets/curso/temas/tema3/img05.png')
      .col-md-6.col-10
        p Los elementos para la construcción de un flujo de caja son cuatro:
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 1
            | Ingresos iniciales o inversión.
          li 
            .lista-ol--cuadro__vineta
              span 2
            | Ingresos y gastos de operación.
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Tiempo o momento en el que se reciben los ingresos y se realizan las erogaciones.
          li 
            .lista-ol--cuadro__vineta
              span 4
            | El valor de desecho o salvamento del proyecto de inversión.
        p Para construir el flujo de fondos se necesita conocer el horizonte de evaluación.

    .h4.mb-4.mt-5(data-aos="zoom-down-right")
      span.titulo-herramientas Estructura de flujo de caja
    
    p La elaboración de un flujo de caja se puede realizar teniendo en cuenta esta estructura general, la cual tiene utilidad de acuerdo con el fin de la evaluación y el objetivo del proyecto, así:

    .row.justify-content-center.align-items-center.mb-4
      .col-md-6.col-10.px-0
        img(src='@/assets/curso/temas/tema3/img06.png')
      .col-md-4.col-10.BG04.p-4
        p.text-bold.mb-0 + Ingresos sujetos a impuestos.
        p.text-bold.mb-0 -	Egresos sujetos a impuestos.
        p.text-bold.mb-0 = Ebitda.
        p.text-bold.mb-0 -	Gastos no desembolsables.
        p.text-bold.mb-0 = Resultado o utilidad antes de impuesto.
        p.text-bold.mb-0 -	Impuestos.
        p.text-bold.mb-0 = Resultado después de impuesto.
        p.text-bold.mb-0 + Ajustes por gastos no desembolsables.
        p.text-bold.mb-0 = Resultado operacional neto.
        p.text-bold.mb-0 -	Egresos no sujetos a impuestos.
        p.text-bold.mb-0 + Beneficios no sujetos a impuestos.
        p.text-bold.mb-0 = Flujo de caja.

    p Para ello es importante tener en cuenta:

    LineaTiempoE.color-primario.mb-4
      .row.align-items-center(titulo="Ingresos")
        .col-lg-2.col-4
          img(src='@/assets/curso/temas/tema3/img07.png')
        .col-10
          p.mb-0 Ingresos sujetos de impuestos son todos los generados por la venta de productos y la venta de activos cuando se da su reemplazo. 
      .row.align-items-center(titulo="Egresos")
        .col-lg-2.col-4
          img(src='@/assets/curso/temas/tema3/img08.png')
        .col-10
          p Los egresos no sujetos a impuestos son la inversión en terrenos, obras físicas y maquinaria, así como la ampliación de la planta o capacidad productiva, la inversión en activos de reemplazo y la inversión en capital de trabajo.
          p En cuanto a los gastos no desembolsables son descontados en el rubro de impuestos, pero que no representan una erogación de dinero como la depreciación, la amortización de los activos intangibles o el valor de un activo en libros. 
          p.mb-0 Para calcular la depreciación a pesar de existir diferentes métodos para calcularla, al construir flujos de caja el criterio para calcular este concepto se basa en el método de línea recta, es decir, supone que se deprecia todo activo en proporción similar cada año por entregar un escenario más conservador.
      .row.align-items-center(titulo="Costos")
        .col-lg-2.col-4
          img(src='@/assets/curso/temas/tema3/img09.png')
        .col-10
          p.mb-0 Son erogaciones sujetas a impuesto y que corresponden a los costos correspondientes a la producción o fabricación de productos a comercializar.

    .h4.mb-4.mt-5(data-aos="zoom-down-right")
      span.titulo-herramientas Beneficios no sujetos a impuestos son el valor de desecho del proyecto

    p El valor de desecho del proyecto de inversión se refiere al valor que tienen los activos adquiridos en el proyecto por el inversionista para conocer luego de sustraer la depreciación a una tasa de retorno solicitada el cual se calcula por tres vías o métodos, a saber:

    .row.justify-content-center.mb-4
      .col-md-4.col-10.mb-md-0.mb-4(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/img10.png' alt='AvatarTop')
          .BG15.p-4.color-secundario.pt-5
            h4.text-center Método contable
            p Es un método conservador para calcular el valor de desecho que se utiliza en etapa de perfil o prefactibilidad y se realiza con la sumatoria de todos los valores contables o en libros de cada activo, teniendo en cuenta la inversión del activo, el número de años de depreciación faltantes y los ya depreciados. 
      .col-md-4.col-10.mb-md-0.mb-4(data-aos="zoom-in")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/img11.png' alt='AvatarTop')
          .BG15.p-4.color-secundario.pt-5
            h4.text-center Método comercial
            p Se determina según el valor comercial que se espera que los activos puedan tener y sus efectos tributarios. Se calcula tomando el valor comercial, la utilidad antes de impuestos, la utilidad neta y el valor contable.
      .col-md-4.col-10(data-aos="fade-left")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/img12.png' alt='AvatarTop')
          .BG15.p-4.color-secundario.pt-5
            h4.text-center Método económico
            p Estima el valor que un inversionista podría pagar por el proyecto y considera el flujo de caja del último año al que se le sustrae el valor de la depreciación y se multiplica por la tasa de retorno exigida. Este es el método más utilizado y aterrizado para calcular el valor de desecho de un proyecto de inversión.

    .h4.mb-4.mt-5(data-aos="zoom-down-right")
      span.titulo-herramientas Flujo de caja del inversionista

    p Este flujo de caja nace de la necesidad de conocer la rentabilidad que recibirá un inversionista al colocar sus recursos propios en un proyecto de inversión para lo cual es necesario incluir el efecto del financiamiento con el fin de incluir el impacto de la deuda. De esta manera, se incluye el costo de la financiación separando el valor de la cuota que asume los gastos financieros y el de amortización o disminución del capital de la obligación financiera.

    .row.justify-content-center.mb-4
      .col-md-6.col-10.px-0(data-aos="fade-right")
        img(src='@/assets/curso/temas/tema3/img13.png')
      .col-md-4.col-10.BG16.p-3(data-aos="fade-left")
        p.text-bold.ms-2.mb-0 + Ingresos sujetos a impuestos.
        p.text-bold.ms-2.mb-0 -Egresos sujetos a impuestos.
        p.text-bold.ms-2.mb-0 = Ebitda.
        p.text-bold.ms-2.mb-0 - Intereses de la obligación.
        p.text-bold.ms-2.mb-0 - Gastos no desembolsables.
        p.text-bold.ms-2.mb-0 = Resultado antes de impuesto.
        p.text-bold.ms-2.mb-0 - Impuesto.
        p.text-bold.ms-2.mb-0 = Resultado después de impuesto.
        p.text-bold.ms-2.mb-0 + Ajustes por gastos no desembolsables.
        p.text-bold.ms-2.mb-0 - Egresos no sujetos a impuestos.
        p.text-bold.ms-2.mb-0 + Beneficios no sujetos a impuestos.
        p.text-bold.ms-2.mb-0 + Préstamo.
        p.text-bold.ms-2.mb-0 - Amortización de la obligación.
        p.text-bold.ms-2.mb-0 = Flujo de caja.

    .h4.mb-4.mt-5(data-aos="zoom-down-right")
      span.titulo-herramientas Flujo de caja de proyectos de inversión en empresa en marcha

    .row.justify-content-center.align-items-center.mb-4
      .col-md-7.col-10.order-md-1
        p El flujo de caja difiere del inversionista, ya que algunos rubros o conceptos ya están siendo asumidos por la operación de la empresa como los gastos de remuneración del conductor de la empresa que viene desarrollando una actividad o proceso en la organización.
        p.mb-0 De esta manera, los conceptos que tienen cabida en este estado financiero son las inversiones que se realizan por reemplazo, ampliación, tercerización de procesos y los de abandono, permitiendo identificar los  proyectos de inversión de reemplazo que tienen origen debido a la reducción del nivel de producción causando el incremento en los costos productivos por inactividad para la realización de mantenimiento asociados a la vida útil agotada del equipo y la obsolescencia.
      .col-md-5.col-8.order-md-2.order-1.order-2.mb-md-0.mb-4
        figure.mb-5(data-aos="fade-left")
          img(src='@/assets/curso/temas/tema3/img14.png')

    p Los proyectos de reemplazo especialmente nacen por las siguientes razones:

    .row.justify-content-center.align-items-center.mb-5
      .col-md-8.BG04.p-4
        .row.justify-content-center.align-items-center
          .col-md-2.col-8.p-0.img01.mb-md-0.mb-4
            figure
              img.w-75(src='@/assets/curso/temas/tema3/img15.png')
          .col-md-10.col-12
            ol.lista-ol--cuadro
              li 
                .lista-ol--cuadro__vineta
                  span a
                | Sustitución de activos sin cambios en los niveles de operación ni de ingresos.
              li 
                .lista-ol--cuadro__vineta
                  span b
                | Sustitución de activos con modificaciones en la productividad, ventas e ingresos.
              li 
                .lista-ol--cuadro__vineta
                  span c
                | Requerida sustitución de activos con o sin cambio en el nivel operativo.

    p.mt-5 Además de relacionar lo que representa:

    .row.justify-content-center.mb-4
      .col-md-8
        .row.justify-content-center.align-items-center.mb-4
          .col-md-2.col-4.mb-md-0.mb-4
            img(src='@/assets/curso/temas/tema3/img16.png')
          .col-md-10
            h4 La ampliación
            p Surge cuando la tecnología vigente tiene poca capacidad, o para complementar e incrementar los niveles de producción.
        hr
        .row.justify-content-center.align-items-center.mb-4
          .col-md-2.col-4.mb-md-0.mb-4
            img(src='@/assets/curso/temas/tema3/img17.png')
          .col-md-10
            h4 La tercerización
            p Trae beneficios al permitir la concentración de esfuerzos, compartir riesgos de inversión con proveedores, liberar recursos de compromisos para dedicarlos a nuevas actividades, generar ingresos por venta de activos e incrementar la eficiencia al entregar actividades de la organización a expertos.
        hr
        .row.justify-content-center.align-items-center
          .col-md-2.col-4.mb-md-0.mb-4
            img(src='@/assets/curso/temas/tema3/img18.png')
          .col-md-10
            h4 Los proyectos de abandono
            p Se caracterizan por eliminar áreas de negocio no rentables liberando recursos para invertirlos en proyectos más rentables.

    p Para este caso los flujos de caja pueden ser de proyecto puro antes conocido como de la situación actual sin proyecto y de la situación con proyecto conocido actualmente como flujo de caja de proyecto puro cuando la inversión por reemplazo se realiza en el año cero (0), realizados con el fin de evidenciar en los mismo las inversiones en el momento real que se realizan y sus efectos en los flujos de caja, así:

    
    AcordionA.mb-5(tipo="a" clase-tarjeta="BG01A")
      .row.justify-content-center(titulo="Estructura del flujo de caja proyecto puro")
        .col-md-5.col-11.order-md-1.order-2.mb-4
          h4 Estructura del flujo de caja proyecto puro 
          p.mb-0 = Ingresos sujetos a impuestos*.
          p.mb-0 - Egresos sujetos a impuestos.
          p.mb-0 - Gastos no desembolsables.
          p.mb-0 - Depreciación.
          p.mb-0 - Valor en libros.
          p.mb-0 = Resultado/Utilidad antes de impuesto.
          p.mb-0 - Impuesto.
          p.mb-0 = Resultado después de Impuesto.
          p.mb-0 + Depreciación.
          p.mb-0 + Valor en libros.
          p.mb-0 = Flujo de caja.
        .col-md-6.col-11.order-md-2.order-1.mb-md-0.mb-4
          img(src='@/assets/curso/temas/tema3/img19.png')
        .col-12.col-md-11.mt-2.BG16.p-4.order-3
          p.mb-0 * Los ingresos corresponden a la venta de activos que por ser originados por reemplazo se realizaría en el último año del horizonte del proyecto.
      .row.justify-content-center(titulo="Estructura del flujo de caja de la situación con proyecto")
        .col-md-5.col-11.order-md-1.order-2.mb-4
          h4 Estructura del flujo de caja de la situación con proyecto 
          p.mb-0 = Ingresos sujetos a impuestos*.
          p.mb-0 + Ahorro costos.
          p.mb-0 - Gastos no desembolsables.
          p.mb-0 -	Valor en libros.
          p.mb-0 = Resultado antes de impuesto.
          p.mb-0 - Impuesto.
          p.mb-0 = Resultado después de impuesto.
          p.mb-0 + Depreciación.
          p.mb-0 + Valor en libros.
          p.mb-0 = Flujo de caja.
        .col-md-6.col-11.order-md-2.order-1.mb-md-0.mb-4
          img(src='@/assets/curso/temas/tema3/img20.png')
        .col-11.BG16.mt-2.p-4.order-3
          p.mb-0 * Los ingresos corresponden a la venta del equipo vigente y el impuesto por pagar por la venta que deben ser incorporados en el año cero (0), porque se realiza la inversión en la compra del activo de reemplazo.
      .row.justify-content-center(titulo="Flujo de caja incremental")
        .col-md-5.col-11.order-md-1.order-2.mb-4
          p Es pertinente anotar que para tomar decisiones de inversión en el caso del reemplazo se hace necesario comparar a través de flujo diferencial para evaluar el impacto de la decisión, este se realiza tomando los flujos de caja netos de la situación sin proyecto o en este caso sin reemplazo y debajo se ubican los flujos de caja netos de la situación con proyecto o para este caso con reemplazo lo que permite calcular las diferencias y valorar el flujo incremental el cual se construye así:
          h4 Flujo de caja incremental 
          p.mb-0 = Ingresos sujetos a impuestos*.
          p.mb-0 + Ahorro costos.
          p.mb-0 + Gastos no desembolsables/Depreciación.
          p.mb-0 -	Valor en libros.
          p.mb-0 = Utilidad antes de impuesto.
          p.mb-0 + Impuesto.
          p.mb-0 = Utilidad neta.
          p.mb-0 + Depreciación.
          p.mb-0 + Valor en libros.
          p.mb-0 -	Inversión.
          p.mb-0 = Flujo de caja.
        .col-md-6.col-11.order-md-2.order-1.mb-md-0.mb-4
          img(src='@/assets/curso/temas/tema3/img21.png')
        .col-11.BG16.p-4.order-3
          p.mb-0 * La financiación de un proyecto depende de la mejor alternativa que el inversionista debe hallar a partir de la elaboración de los flujos de costos de cada opción de financiación con el fin de elegir las más apropiada siendo esta la que represente el menor valor actual de costos de capital.

    .h4.mb-4.mt-5(data-aos="zoom-down-right")
      span.titulo-herramientas Evaluación financiera
    
    p.mb-5 Al tener un proyecto de inversión se tiene claro que esta se realiza con el objeto de lograr un incremento de la inversión generando valor a la organización. Es decir, no es suficiente que al evaluar los flujos de caja anualmente estos sean positivos sin desconocer que muchos de ellos proyectos a emprender en una empresa están ligados a la incertidumbre de los resultados existen dos instrumentos altamente aceptados para realizar este análisis en su evaluación: valor presente neto y tasa interna de retorno. A continuación, se detalla cómo se presenta la evaluación financiera.
    .BG16.pt-4.px-4.mb-4
      LineaTiempoC.color-acento-contenido(text-small)
        .row.justify-content-center.p-3(titulo="VPN")
          .col-12.mb-4.mb-md-0
            h4 VPN
            p Se reconoce como el indicador resultado de sustraer del valor presente de los futuros flujos de caja la inversión inicial. Es adecuado precisar que la tasa de interés corresponde a la mínima rentabilidad que deben producir los bienes o activos que posee una empresa conocida también como tasa de oportunidad.
            p También puede definirse como Valor Actual Neto o (VAN) que es aceptable cuando es igual o superior a cero, lo cual quiere decir que al restar todos los ingresos y erogaciones el proyecto de inversión no presenta riesgos puesto que no pierde su inversión o lo que es mejor, si el valor es mayor a cero quiere decir que la inversión genera beneficios expresados en la cantidad que arroje como resultado.
            p Si el horizonte del proyecto es de 5 años el número de flujos de caja a descontar son 5 a la tasa de interés definida por la organización o el inversionista, su fórmula es:
            p <span style="background-color:#3AE3FE !important; font-weight: bold; padding: 5px">VPN = - I0 + (F/(1 + i)n) + (F/(1 + i)n) + (F/(1 + i)n) + … </span>
            p Estos son los criterios para decidir con base en VPN:
            p.text-bold 1. Si VPN &gt; 0, entonces el proyecto es aceptable.
            p.text-bold 2. Si VPN &lt; 0, entonces el proyecto no es aceptable.
            p.text-bold 3. Si VPN = 0, entonces es indiferente aceptarlo o no.
        .row.justify-content-center.p-3(titulo="TIR")
          .col-12.mb-4.mb-md-0
            h4 TIR
            p Es un instrumento para medir la rentabilidad que ofrece una inversión y la viabilidad para llevarla a cabo. Definida como la tasa de interés que hace equivalentes los ingresos y egresos tomando como primer egreso la inversión inicial del proyecto, también puede definirse como la tasa de interés que equilibra o  iguala en el tiempo los ingresos y egresos de un proyecto. Representa la tasa de interés más alta que un inversionista puede pagar sin perder su inversión. La fórmula es:
            p <span style="background-color:#3AE3FE !important; font-weight: bold; padding: 5px">TIR = - I0 +(F/(1 + i)n) + (F/(1 + i)n) + (F/(1 + i)n)…</span>
            p Los criterios de selección del proyecto de inversión según TIR, es:
            p.text-bold 1. Si TIR &gt; K, el proyecto será aceptado. Teniendo una rentabilidad mayor a la tasa mínima esperada o al Costo de Capital (CK).
            p.text-bold 2.Si TIR = K el proyecto será aceptado si existe la probabilidad de mejorar la posición en el mercado porque no presenta beneficios o rentabilidad.
            p.text-bold 3. Si TIR &lt; K, el proyecto debe rechazarse debido a que no cubre la rentabilidad mínima esperada.
        .row.justify-content-center.p-3(titulo="CAUE")
          .col-12.mb-4.mb-md-0
            h4 CAUE
            p Indica Costo Anual Uniforme Equivalente llamado también flujo final de caja y representa la cantidad de flujos de caja que el proyecto de inversión espera recibir por un número n de periodos a una tasa de interés transformando todos lo ingreso y egresos en pagos uniformes o anualidades.
            p <span style="background-color:#3AE3FE !important; font-weight: bold; padding: 5px">CAUE = - I0 +(F/(1 + i)n) + (F/(1 + i)n) + (F/(1 + i)n)… donde i = TIO</span>
            p Los criterios para aceptar o rechazar un proyecto de inversión bajo este indicador es:
            p.text-bold 1. Si el CAUE es positivo, los ingresos son mayores que los egresos y genera beneficios y rentabilidad.
            p.text-bold 2. Si el CAUE es negativo, los ingresos son menores que los egresos y el proyecto genera pérdidas.
        .row.justify-content-center.p-3(titulo="ROI")
          .col-12.mb-4.mb-md-0
            h4 Periodo de Recuperación de la Inversión - ROI
            p Determina el número de periodos o tiempo expresado en “n” cual fuere los períodos en el flujo de caja, que pueden ser mensuales, bimensuales, trimestrales, semestrales anuales requeridos o necesarios para recuperar la inversión, en otras palabras, compara la inversión inicial con los flujos de caja del proyecto en valores absolutos sin la intervención de una tasa de interés. Donde I0 corresponde a la inversión inicial y F corresponde a la sumatoria de los flujos de caja obtenidos durante el horizonte del proyecto de inversión.
            p.text-bold ROI = ln / F
        .row.justify-content-center.p-3(titulo="TIO")
          .col-12.mb-4.mb-md-0
            h4 TIO
            p Tasa de Interés de Oportunidad (TIO), corresponde a la tasa o beneficio que un inversionista espera recibir por invertir su dinero en x proyecto y dejar de invertirlo en otro que podría hipotéticamente generarle mayores beneficios.
        .row.justify-content-center.p-3(titulo="ANF")
          .col-12.mb-4.mb-md-0
            h4 Activo Neto Financiado (ANF)
            p También conocido como Capital Invertido Neto (CIN), son los activos que han sido financiados con servicio a la deuda representados en pasivos costosos o con recursos del patrimonio, siendo el patrimonio el recurso  donde el costo se hace más elevado debido a que los inversionistas siempre esperan un beneficio mayor a cualquiera que reciba un acreedor. 
            p <span style="background-color:#3AE3FE !important; font-weight: bold; padding: 5px">ANF = patrimonio + pasivos con costo</span>
            p Al identificar los pasivos con costo se refiere a las obligaciones financieras cuyo costo corresponde al servicio a la deuda o gastos financieros a pagar por este servicio, entre los cuales se encuentran obligaciones financieras de corto y largo plazo, los bonos, los pasivos con socios.

    .h4.mb-4.mt-5(data-aos="zoom-down-right")
      span.titulo-herramientas Costo Promedio de Capital (CPC)
    
    p Se define con el fin de determinar el costo del patrimonio siendo los dueños quienes fijan la tasa de retorno superior a la fijada por los acreedores. Para calcularlo se toma el costo de cada pasivo costoso y la tasa de oportunidad (TIO) esperada por los socios, luego cada renglón se pondera por su respectiva participación del total de recursos costosos. Para calcularlo se va a tomar la información del estado de situación financiera de Saloan:

    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
      h5 Tabla 6.
      em Costo promedio de capital

    table.mb-4(data-aos="fade-right")
      tr
        th(style="background-color: #3AE3FE;" colspan="2").text-center Recurso
        th(style="background-color: #3AE3FE;").text-center Tasa
        th(style="background-color: #3AE3FE;").text-center Participación
        th(style="background-color: #3AE3FE;").text-center Ponderación
      tr
        td(style="background-color: #F6F6F6;") Pasivo corriente
        td(style="background-color: #F6F6F6;").text-end 25.000.000
        td(style="background-color: #F6F6F6;").text-end 26,82 %
        td(style="background-color: #F6F6F6;").text-end 14,88 %
        td(style="background-color: #F6F6F6;").text-end 3,99
      tr
        td Pasivo a Largo Plazo
        td.text-end 50.000.000
        td.text-end 26,82 %
        td.text-end 29,76 %
        td.text-end 7,98
      tr
        td(style="background-color: #F6F6F6;") Patrimonio
        td(style="background-color: #F6F6F6;").text-end 93.000.000
        td(style="background-color: #F6F6F6;").text-end 29 %
        td(style="background-color: #F6F6F6;").text-end 55,36 %
        td(style="background-color: #F6F6F6;").text-end 16,05
      tr
        th Totales
        th.text-end 168.000.000
        th.text-end 27,54%
        th.text-end 100 %
        th.text-end 28,02 %
      tr
        td(style="background-color: #F6F6F6;" colspan="5") Fuente: Propia
    
    .row.justify-content-center.align-items-center.mb-4
      .col-md-5.col-8.mb-md-0.mb-4
        figure.mb-5(data-aos="fade-right")
          img(src='@/assets/curso/temas/tema3/img22.png')
      .col-md-7.col-10
        p Para calcular la TIO primero se investigó acerca de la tasa efectiva anual que cobran actualmente las entidades financieras siendo esta de 26,82 % como la tasa de los socios debe ser superior se fija en 2,18 puntos por encima, luego se calcula el promedio realizando la sumatoria de las tasas y dividiendo en 3 que son el número de recursos registrados.  
        p Para calcular la participación del recurso se divide el valor de cada recurso sobre el valor total convirtiendo a porcentaje ese resultado, la sumatoria de la participación debe ser igual a 100 %.
        p La ponderación se obtiene de multiplicar la tasa de cada recurso por su participación esto nos arroja un nuevo porcentaje o ponderación.
        p La interpretación de este indicador se facilita cuando hay dos o más alternativas de inversión donde se aplique y se defina cuál de ellas es la menos costosa para la organización. Sin embargo, este componente o indicador individual aporta al cálculo del EVA que se estará tratando más adelante.

    .BG01.p-4.mb-5(data-aos="fade-right")
      SlyderA(tipo="b")
        .row.justify-content-center
          .col-md-11.col-12
            h4 Utilidad Neta Ajustada (UNA)
            p Se refiere a la utilidad antes de impuestos y de gastos financieros. Lo que se pretende es definir si esta utilidad neta ajustada es suficiente para atender el costo de los recursos en pasivos, patrimonio y aportar a la generación de riqueza en la organización. Para su cálculo se necesita:
            p.text-center <span style="background-color:#3AE3FE !important; font-weight: bold; padding: 6px">UNA = Utilidad neta + Gastos financieros</span>
        .row.justify-content-center
          .col-md-11.col-12
            h4 EVA
            p Quiere decir valor económico agregado, es un indicador creado para crear riqueza basado en la eficiencia y productividad de los bienes y derechos de la empresa o activos, la estructura del capital y el medio al que la empresa pertenece. Su fórmula es:
            p.text-center <span style="background-color:#3AE3FE !important; font-weight: bold; padding: 5px">EVA = UNA - (ANF x CPC)</span>
            p.mb-0.text-bold EVA: Economic Value Added (valor económico agregado).
            p.mb-0.text-bold UNA: Utilidad Neta Ajustada.
            p.mb-0.text-bold ANF: Activo Neto Financiado.
            p.mb-0.text-bold CPC: Costo Promedio de Capital.
        //- .row.justify-content-center
        //-   .col-md-11.col-12

    p Su fin es evaluar las estrategias a implementar tendientes a aumentar el valor de la empresa basado en los objetivos estratégicos, operacionales y financieros, los recursos invertidos, el riesgo y el beneficio a obtener.
    p A continuación, se desarrolla un ejemplo para ampliar la aplicación de indicadores y su interpretación:     

    .row.justify-content-center.mb-4
      .col-md-10.BG18.p-4
        p La empresa Saloan ha decidido tecnificar aún más su proceso productivo y ha determinado que realizará una inversión en nueva tecnología para el proceso productivo en el año 3 con el fin de reducir los costos de producción, incrementar sus ventas, ser más productiva y generar riqueza.
      .col-md-5.col-6.px-0(data-aos="fade-right")
        img(src='@/assets/curso/temas/tema3/img23.png')
      .col-md-5.col-8.BG01.p-4(data-aos="fade-left")
        p.mb-0 El escenario actual de la empresa es:
        p.mb-0 #[strong Ventas]: 3333 unidades/año
        p.mb-0 #[strong Precio de venta]: $15.000
        p.mb-0 #[strong Costo de producción]: $12.000
        p.mb-0 #[strong Depreciación]: $12'000.000
        p.mb-0 #[strong Gastos de administración]: 15 % sobre ventas
        p.mb-0 #[strong Inversión]: $100'000.000
        p.mb-0 #[strong Recursos propios]: el 60 % de la inversión
        p.mb-0 #[strong Momento de la inversión]: año 3
        p.mb-0 A partir del año 4 se reducen los costos de producción en 50 %
        p.mb-0 #[strong Valor en libros]: $4'000.000
        p.mb-0 #[strong Venta de activo]: $8'000.000
        p.mb-0 Incremento de ventas a partir del año 4 en 50 %
        p.mb-0 #[strong Impuesto]: 35 %
        p.mb-0 #[strong Préstamo]: $40'000.000
        p.mb-0 #[strong i]: 26,82 % E.A.
        p.mb-0 #[strong n]: 4 años
        p.mb-0 #[strong A]: $xxx? Anual
        p.mb-0 #[strong TIO]: 29 %
        p.mb-0 #[strong Hallar]: VPN, TIR y Serie de cuotas anuales y conclusión.
        
    p Para desarrollar el ejercicio se debe elaborar la tabla de amortización de la obligación. En este caso no se requiere realizar la conversión de tasa de interés porque la cancelación se realizará con 1 cuota anual durante 4 años; por tanto, se utiliza una tasa del 26,82 % EA.
    p Para construir la tabla del crédito se necesita conocer al valor de la cuota en los términos del crédito, así:

    .row.justify-content-center.mb-4
      .col-md-10.mb-4
        img(src='@/assets/curso/temas/tema3/img24.svg')
      .col-md-10.mb-4
        .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
          h5 Tabla 7.
          em Amortización

        table.mb-4(data-aos="fade-right")
          tr
            th(style="background-color: #3AE3FE;").text-center n
            th(style="background-color: #3AE3FE;").text-center Serie de cuotas o anualidades A
            th(style="background-color: #3AE3FE;").text-center Interés B
            th(style="background-color: #3AE3FE;").text-center Amortización C = A -B
            th(style="background-color: #3AE3FE;").text-center Saldo = n - C
          tr
            td(style="background-color: #F6F6F6;").text-center 0
            td(style="background-color: #F6F6F6;").text-end -
            td(style="background-color: #F6F6F6;").text-end -
            td(style="background-color: #F6F6F6;").text-end -
            td(style="background-color: #F6F6F6;").text-end 40.000.000,00
          tr
            td.text-center 1
            td.text-end 17.489.077,31
            td.text-end 10.728.000,00
            td.text-end 6.761.077,31
            td.text-end 33.238.922,69
          tr
            td(style="background-color: #F6F6F6;").text-center 2
            td(style="background-color: #F6F6F6;").text-end 17.489.077,31
            td(style="background-color: #F6F6F6;").text-end 8.914.679,07
            td(style="background-color: #F6F6F6;").text-end 8.574.398,25
            td(style="background-color: #F6F6F6;").text-end 24.664.524,44
          tr
            td.text-center 3
            td.text-end 17.489.077,31
            td.text-end 6.615.025,46
            td.text-end 10.874.051,85
            td.text-end 13.790.472,59
          tr
            td(style="background-color: #F6F6F6;").text-center 4
            td(style="background-color: #F6F6F6;").text-end 17.489.077,31
            td(style="background-color: #F6F6F6;").text-end 3.698.604,75
            td(style="background-color: #F6F6F6;").text-end 13.790.472,59
            td(style="background-color: #F6F6F6;").text-end 0
    
    p La tabla de amortización siempre debe dar en su saldo final cero, por esa razón se utilizan todos los decimales parecer algo imperceptible, pero al tomar solo dos decimales la cuota era por $17.492.000 y al finalizar arrojaba un saldo final de $17.000, aproximadamente.

    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
      h5 Tabla 8.
      em Flujo de caja

    table.mb-4(data-aos="fade-right")
      tr
        th(style="background-color: #3AE3FE;").text-center
        th(style="background-color: #3AE3FE;").text-center Concepto
        th(style="background-color: #3AE3FE;").text-center Año 0
        th(style="background-color: #3AE3FE;").text-center Año 1
        th(style="background-color: #3AE3FE;").text-center Año 2
        th(style="background-color: #3AE3FE;").text-center Año 3
        th(style="background-color: #3AE3FE;").text-center Año 4
        th(style="background-color: #3AE3FE;").text-center Año 5
      tr
        td.text-bold(style="background-color: #3AE3FE;").text-center =
        td.text-bold Ingresos sujetos a impuestos
        td.text-bold.text-end 
        td.text-bold.text-end 49.995.000,00
        td.text-bold.text-end 49.995.000,00
        td.text-bold.text-end 49.995.000,00
        td.text-bold.text-end 74.992.500,00
        td.text-bold.text-end 74.992.500,00
      tr
        td(style="background-color: #3AE3FE;").text-center +
        td(style="background-color: #F6F6F6;") Venta de activo
        td(style="background-color: #F6F6F6;").text-end
        td(style="background-color: #F6F6F6;").text-end
        td(style="background-color: #F6F6F6;").text-end
        td(style="background-color: #F6F6F6;").text-end 8.000.000,00
        td(style="background-color: #F6F6F6;").text-end
        td(style="background-color: #F6F6F6;").text-end
      tr
        td.text-center(style="background-color: #3AE3FE;") -
        td Costos de producción
        td.text-end 
        td.text-end -39.996.000,00
        td.text-end -39.996.000,00
        td.text-end -39.996.000,00
        td.text-end -19.998.000,00
        td.text-end -19.998.000,00
      tr
        td(style="background-color: #3AE3FE;").text-center -
        td(style="background-color: #F6F6F6;") Gastos de administración
        td(style="background-color: #F6F6F6;").text-end
        td(style="background-color: #F6F6F6;").text-end -7.499.250,00
        td(style="background-color: #F6F6F6;").text-end -7.499.250,00
        td(style="background-color: #F6F6F6;").text-end -7.499.250,00
        td(style="background-color: #F6F6F6;").text-end -7.499.250,00
        td(style="background-color: #F6F6F6;").text-end -7.499.250,00
      tr
        td.text-center(style="background-color: #3AE3FE;") -
        td Gastos Financieros obligación
        td.text-end 
        td.text-end -10.728.000,00
        td.text-end -8.914.679,07
        td.text-end -6.615.025,46
        td.text-end -3.698.604,75
        td.text-end -
      tr
        td(style="background-color: #3AE3FE;").text-center +
        td(style="background-color: #F6F6F6;") Depreciación
        td(style="background-color: #F6F6F6;").text-end
        td(style="background-color: #F6F6F6;").text-end -12.000.000,00
        td(style="background-color: #F6F6F6;").text-end -12.000.000,00
        td(style="background-color: #F6F6F6;").text-end -12.000.000,00
        td(style="background-color: #F6F6F6;").text-end -12.000.000,00
        td(style="background-color: #F6F6F6;").text-end -12.000.000,00
      tr
        td.text-center(style="background-color: #3AE3FE;") -
        td Valor en libros
        td.text-end 
        td.text-end 
        td.text-end 
        td.text-end -4.000.000,00
        td.text-end 
        td.text-end
      tr
        td(style="background-color: #3AE3FE;").text-bold.text-center =
        td(style="background-color: #F6F6F6;").text-bold Resultado antes de impuesto
        td(style="background-color: #F6F6F6;").text-bold.text-end
        td(style="background-color: #F6F6F6;").text-bold.text-end -20.228.250,00
        td(style="background-color: #F6F6F6;").text-bold.text-end -18.414.929,07
        td(style="background-color: #F6F6F6;").text-bold.text-end -12.115.275,46
        td(style="background-color: #F6F6F6;").text-bold.text-end 31.796.645,25
        td(style="background-color: #F6F6F6;").text-bold.text-end 35.495.250,00
      tr
        td.text-center(style="background-color: #3AE3FE;") -
        td Impuesto
        td.text-end 
        td.text-end -7.079.887,50
        td.text-end -6.445.225,17
        td.text-end -4.240.346,41
        td.text-end -11.128.825,84
        td.text-end -12.423.337,50
      tr
        td(style="background-color: #3AE3FE;").text-bold.text-center =
        td(style="background-color: #F6F6F6;").text-bold Resultado neto
        td(style="background-color: #F6F6F6;").text-bold.text-end
        td(style="background-color: #F6F6F6;").text-bold.text-end -27.308.137,50
        td(style="background-color: #F6F6F6;").text-bold.text-end -24.860.154,24
        td(style="background-color: #F6F6F6;").text-bold.text-end -16.355.621,87
        td(style="background-color: #F6F6F6;").text-bold.text-end 20.667.819,41
        td(style="background-color: #F6F6F6;").text-bold.text-end 23.071.912,50
      tr
        td.text-center(style="background-color: #3AE3FE;") +
        td Depreciación
        td.text-end 
        td.text-end 12.000.000,00
        td.text-end 12.000.000,00
        td.text-end 12.000.000,00
        td.text-end 12.000.000,00
        td.text-end 12.000.000,00
      tr
        td(style="background-color: #3AE3FE;").text-center +
        td(style="background-color: #F6F6F6;") Valor en libros
        td(style="background-color: #F6F6F6;").text-end
        td(style="background-color: #F6F6F6;").text-end 
        td(style="background-color: #F6F6F6;").text-end 
        td(style="background-color: #F6F6F6;").text-end 4.000.000,00
        td(style="background-color: #F6F6F6;").text-end -
        td(style="background-color: #F6F6F6;").text-end -
      tr
        td.text-center(style="background-color: #3AE3FE;") -
        td Inversión de reemplazo
        td.text-end -
        td.text-end -
        td.text-end -
        td.text-end -100.000.000,00
        td.text-end -
        td.text-end -
      tr
        td(style="background-color: #3AE3FE;").text-center +
        td(style="background-color: #F6F6F6;") Préstamo
        td(style="background-color: #F6F6F6;").text-end
        td(style="background-color: #F6F6F6;").text-end 
        td(style="background-color: #F6F6F6;").text-end 
        td(style="background-color: #F6F6F6;").text-end 40.000.000,00
        td(style="background-color: #F6F6F6;").text-end -
        td(style="background-color: #F6F6F6;").text-end -
      tr
        td.text-center(style="background-color: #3AE3FE;") -
        td Amortización de la obligación
        td.text-end 
        td.text-end -6.761.077,31
        td.text-end -8.574.398,25
        td.text-end -10.874.051,85
        td.text-end -13.790.472,59
        td.text-end -
      tr
        td(style="background-color: #3AE3FE;").text-center -
        td(style="background-color: #F6F6F6;") Valor de desecho
        td(style="background-color: #F6F6F6;")
        td(style="background-color: #F6F6F6;") 
        td(style="background-color: #F6F6F6;") 
        td(style="background-color: #F6F6F6;")
        td(style="background-color: #F6F6F6;")
        td(style="background-color: #F6F6F6;").text-end 0,00
      tr
        td.text-bold.text-center(style="background-color: #3AE3FE;") =
        td.text-bold Flujo de caja
        td.text-bold.text-end 
        td.text-bold.text-end -14.989.327,31
        td.text-bold.text-end -14.989.327,32
        td.text-bold.text-end -66.989.327,31
        td.text-bold.text-end 30.006.172,66
        td.text-bold.text-end 47.495.250,00

    .BG01.p-4.mb-5(data-aos="fade-right")
      SlyderA.mb-4(tipo="b")
        .row.justify-content-center
          .col-11
            p.mb-0.text-bold VPN o VAN
            p.mb-2.text-bold VPN = - I0 + (F/(1 + i)n) + (F/(1 + i)n) + (F/(1 + i)n) + …
            p.mb-2.text-bold VPN = - 100.000.000 + (-14.989.327,31/(1 + ,29)1) + (-14.989.327,32/(1 + .29)2) + (-66.989.327,31/(1 + i)3) + (30.006.172,66/(1 + ,29)4) +(47.495.250/(1 + ,29)5)
            p.mb-0.text-bold VPN = - 100.000.000 + (-11.619.633,57) + (-9.007.467.89) + (-31.205.588,71) + (10.835.570)+(13.294.566,9)
            p.mb-2.text-bold VPN = -127.702.553,3 
            p Según el indicador de VPN en el escenario que se plantea el proyecto y con una TIO de 29 % en un horizonte de 5 años se debe rechazar el proyecto, si se revisa el flujo de caja la empresa se debe enfrentar a otras fuentes de financiación para ejecutar este proyecto, pero los resultados propuestos, según el flujo de caja son apropiados, es decir, el incremento en las ventas y la reducción de costos pero el proyecto en actuales condiciones requiere un horizonte más amplio para arrojar resultados beneficiosos para la empresa.
        .row.justify-content-center
          .col-11
            p.mb-2.text-bold TIR = - I0 +(F/(1 + i)n) + (F/(1 + i)n) + (F/(1 + i)n)…
            p.mb-2.text-bold TIR = - 100.000.000 + (-14.989.327,31/(1 + ,2682)1) + (-14.989.327,32/(1 +,2682)2) + (-66.989.327,31/(1 + ,2682)3) + (30.006.172,66/(1 + ,2682)4) +(47.495.250/(1 + ,2682)5)
            p.mb-2.text-bold TIR = -100.000.000 + (-11.819.371,79) + (-9.319.801,14) + (-32.842.965,96) + (11.600.043,25) + (14.478.095,39)
            p.mb-2.text-bold TIR = -127.904.000
            p.mb-0 De acuerdo con el resultado de la TIR se confirma la conclusión dada con la aplicación del VPN si la empresa cuenta con fuentes para asumir el proyecto en las condiciones planteadas, puede ejecutar el proyecto sí y solo sí amplía el horizonte del proyecto.

    .h4.mb-4.mt-5(data-aos="zoom-down-right")
      span.titulo-herramientas Evaluación social

    .row.justify-content-center.align-items-center.mb-4
      .col-md-7.col-10.order-md-1.order-2
        p Se enfoca en analizar los beneficios y costos de un proyecto de inversión en determinada comunidad de un territorio. Este tipo de evaluación se enfoca a diferencia de la evaluación financiera en los precios sombra o sociales, valorando los efectos internos y las externalidades que generan bienestar a la comunidad.
        p.mb-0 Como es ampliamente conocido, aunque un proyecto sea financieramente viable no necesariamente lo es para la comunidad, para validar los beneficios de un proyecto o actividad económicamente rentable desde la evaluación social se pueden corregir los factores, aplicando un criterio de corrección definidos sobre beneficios directos, indirectos e intangibles y las externalidades. De esta manera, se hace necesario profundizar acerca de la evaluación social, con la siguiente información: 
      .col-md-5.col-8.order-md-2.order-1.mb-md-0.mb-4
        figure.mb-5(data-aos="fade-left")
          img(src='@/assets/curso/temas/tema3/img25.png')
    
    .row.justify-content-center.mb-5.md-px-5
      .col-lg-3.col-md-6.col-12.mb-4.mb-xl-0.mt-2
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema3/img26.png", alt="alt")
          .crd_hover_txt--body
            ul.lista-ul--color
              li.mb-4
                i.ico-open-task
                h5 Beneficios directos
            p.mb-0 Calculados sobre el aumento o beneficio que traerá la implementación de una decisión, estrategia o proyecto al valorar la venta de sus productos con los precios del mercado, siendo el precio social el precio del mercado ajustado de acuerdo con el factor o criterio establecido y teniendo en cuenta las compras de materias primas e insumos los precios deben ser corregidos al igual que los beneficios.

      .col-lg-3.col-md-6.col-12.mb-4.mb-xl-0.mt-2
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema3/img27.png", alt="alt")
          .crd_hover_txt--body
            ul.lista-ul--color
              li.mb-4
                i.ico-open-task
                h5 Beneficios indirectos
            p Se estiman basados en las transformaciones que surgen de la implementación de una decisión o proyecto en cuanto a producción y consumo de bienes y servicios en un país. 

      .col-lg-3.col-md-6.col-12.mb-4.mb-xl-0.mt-2
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema3/img28.png", alt="alt")
          .crd_hover_txt--body
            ul.lista-ul--color
              li.mb-4
                i.ico-open-task
                h5 Beneficios intangibles
            p No son cuantificables, pero deben considerarse de manera cualitativa para estimar los efectos de la implementación y el bienestar que genera en la comunidad o partes interesadas.
      .col-lg-3.col-md-6.col-12.mb-4.mb-xl-0.mt-2
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema3/img29.png", alt="alt")
          .crd_hover_txt--body
            ul.lista-ul--color
              li.mb-4
                i.ico-open-task
                h5 Externalidades
            p Son factores positivos o negativos en el medio o entorno donde se pretende implementar un proyecto, y se consideran también con los efectos positivos y negativos que pudieran ocasionar. Dentro de ellos se reconoce la política económica y social.


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
