<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Matemática financiera

    p.mb-4 A continuación, se presentan la incidencia de las matemáticas financieras en la organización:

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-12
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 <b>Figura 4. </b> <i>Aspectos presentes en el análisis financiero vertical </i>
        figure
          img.d-none.d-sm-none.d-md-block(src='@/assets/curso/temas/tema1/fig04a.svg', alt='Imagen que presentan la incidencia de las matemáticas financieras en la organización.')  
          img.d-block.d-md-none(src='@/assets/curso/temas/tema1/fig04b.svg', alt='Imagen que presentan la incidencia de las matemáticas financieras en la organización.') 
          
    //- .row.justify-content-center.align-items-center.mb-4
    //-   .col-lg-3.col-6.order-lg-1.order-2(data-aos="fade-right")
    //-     .BG10.p-4.mb-4
    //-       h4 Toma de decisiones
    //-       p  A fin de que el personal en el área de contabilidad y finanzas domine estas técnicas, de manera que a través de su uso potencien los recursos de la organización a través de decisiones acertadas y proactivas que conduzcan a la toma de decisiones que aporten a generar valor al capital.
    //-     .BG11.p-4
    //-       h4 Análisis financiero
    //-       p Esta ciencia aporta al análisis financiero, al permitir determinar el costo de una decisión de financiación, determinar la rentabilidad a recibir en un lapso por una inversión, definir una apropiada política de descuento orientada a los clientes.
    //-   .col-lg-6.col-md-10.order-lg-2.order-1(data-aos="zoom-in")
    //-     figure
    //-       img(src='@/assets/curso/temas/tema2/img01.png')
    //-     .BG14.p-3
    //-       h4.text-center.text-white.mb-0 Matemática Financiera
    //-     .BG01.p-4
    //-       .row.align-items-center.justify-content-center 
    //-         .col-lg-2.col-md-3.col-4.mb-md-0.mb-4
    //-           img(src='@/assets/curso/temas/tema2/img02.png')
    //-         .col-md-8.col-10
    //-           p.mb-0 Las matemáticas financieras son también conocidas como ingeniería económica y manifiestan su importancia en las inversiones, estas acopian una serie de técnicas que permiten al directivo conocer y manejar el concepto de tasa de interés por su uso frecuente en el ámbito organizacional.
    //-   .col-lg-3.col-6.order-3.mt-lg-0.mt-4(data-aos="fade-left")
    //-     .BG12.p-4.mb-4
    //-       h4 Gestión apropiada de los costos
    //-       p Seleccionar la mejor alternativa para la amortización de obligaciones de acuerdo con la liquidez de la empresa, hallar el costo de capital, aportar a una gestión apropiada de los costos y contar con las herramientas para evaluar un proyecto.
    //-     .BG13.p-4
    //-       h4 Valor del dinero en el tiempo
    //-       p Uno de esos conceptos que trata esta ciencia se origina en el valor del dinero en el tiempo, este pierde su valor al transcurrir el tiempo cuando la inflación hace que se desvalorice, lo que influye en la decisión de recibir el dinero hoy o esperar hasta recibirlo en un tiempo determinado.

    .row.justify-content-center.mb-4(data-aos="fade-left")
      .col-12
        p.mb-0 Dado lo anterior, se recibe entonces como beneficio un valor adicional, lo que implica que el dinero en mención es el capital, el excedente a recibir es un beneficio y que este surge por causa de la tasa de interés.<br><br>
        p.mb-0 De aquí la importancia de la matemática financiera en las organizaciones, pues brinda un panorama mucho más cercano a la realidad, a través de técnicas e instrumentos que permiten dilucidar el resultado de una decisión en un futuro. Para ello, se invita a observar los elementos que se integran en las matemáticas financieras para ser aplicadas: 
    
    .BG04.p-4.mb-4(data-aos="fade-left")
      SlyderA.mb-4(tipo="b")
        .row.justify-content-center
          .col-md-4.mb-md-0.mb-2
            h4 Valor futuro 
            p Hace alusión al dinero que esperamos recibir por una inversión en un período de tiempo. Sirve para establecer el beneficio que se obtendrá al invertir una xxx cantidad de dinero durante un periodo de tiempo, la fórmula para calcularlo es:
          .col-md-8
            img.d-none.d-sm-none.d-md-block(src='@/assets/curso/temas/tema2/img03.svg')
            img.d-block.d-md-none(src='@/assets/curso/temas/tema2/img03b.svg')
        .row.justify-content-center
          .col-md-4.mb-md-0.mb-2
            h4 Valor presente
            p Se refiere al valor que tiene hoy una cantidad de dinero, que esperamos recibir como beneficio de una inversión o que debemos cancelar en un futuro por el beneficio de haber recibido esa financiación. A continuación, se presenta la fórmula para su cálculo.
          .col-md-8
            img.d-none.d-sm-none.d-md-block(src='@/assets/curso/temas/tema2/img04.svg')
            img.d-block.d-md-none(src='@/assets/curso/temas/tema2/img04b.svg')
        .row.justify-content-center
          .col-md-8.mb-md-0.mb-4.col-lg-9
            h4 Tasa de interés 
            p.mb-0 Corresponde al costo o renta correspondiente al uso de capital por determinado tiempo. Se representa con la letra “i” y su fórmula es:
            p i = F - P
            p.mb-1 Existen tres tipos relevantes de interés: simple, compuesto y continuo.
            p.mb-1 #[b Interés simple:] es la renta por el uso de un capital que no generan más intereses o no ganan más intereses en el periodo siguiente. Lo que quiere decir que los intereses se calculan siempre por el capital y este permanece constante durante el tiempo que esté vigente esta operación.
            p.mb-1 #[b Interés compuesto:] es el interés generado que al final del periodo capitaliza los intereses devengados en el periodo inmediatamente anterior. En esta operación los intereses ganan intereses, lo que implica que los intereses devengados en un período forman parte del capital en el periodo siguiente.
            p.mb-1 Un porcentaje que indica el valor del dinero en el tiempo, también puede definirse como la cifra que hace equivalentes dos valores diferentes, en diferentes momentos de tiempo. Existen diferentes tasas de interés, así:
          .col-md-4.col-lg-3
            img(src='@/assets/curso/temas/tema2/img05.svg')
        .row.justify-content-center
          .col-md-5.mb-md-0.mb-2
            h4 Valor del dinero en el tiempo
            p Se refiere a la capacidad del dinero en el tiempo de generar mayor valor al dinero o en otras palabras, de generar riqueza. Este valor es el que nos permite hallar las matemáticas financieras a través de su fórmula de valor presente para conocer el valor del dinero hoy y de conocer el valor futuro de una inversión u obligación según fuere el caso.
            p Las matemáticas financieras son útiles para trabajar anualidades, es decir, con el fin de determinar las cuotas a pagar para cubrir una inversión que se espera recuperar junto con su beneficio o tasa de interés a un término definido y una  tasa de interés específica.
          .col-md-7
            img.d-none.d-sm-none.d-md-block(src='@/assets/curso/temas/tema2/img06.svg')
            img.d-block.d-md-none(src='@/assets/curso/temas/tema2/img06b.svg')
        .row.justify-content-center
          .col-md-5.mb-md-0.mb-2
            p También es posible conocer el valor presente a invertir a partir de una serie de cuotas o anualidades y aplica en el caso de realizar una compra de un apartamento sobre planos, que tiene previsto su finalización entidad financiera por el 60 % del valor total del inmueble y, por último, necesita saber el valor de las cuotas a pagar durante un año a la firma constructora para cubrir el excedente restante. En este caso la fórmula es:
          .col-md-7
            img.d-none.d-sm-none.d-md-block(src='@/assets/curso/temas/tema2/img07.svg')
            img.d-block.d-md-none(src='@/assets/curso/temas/tema2/img07b.svg')

    .h4.mb-4.mt-5(data-aos="zoom-down-right")
      span.titulo-herramientas Análisis

    .row.justify-content-center.align-items-center.mb-4
      .col-md-7.col-10.order-md-1.order-2.px-lg-1
        p El análisis es la función principal que cumple la matemática financiera, ella proporciona diferentes herramientas que hacen posible conocer escenarios desconocidos en diferentes circunstancias, los cuales aportan al exitoso desempeño organizacional. Para analizar los anteriores conceptos, a continuación, se desarrolla un ejercicio de aplicación:
        p.mb-0 El inversionista está programando un viaje de turismo en un año que según cotizaciones le costará $15.000.000, actualmente cuenta con dinero disponible para invertir y desea que el beneficio sumado a la inversión corresponda mínimo al valor del viaje, para esto se ha informado que la tasa de interés efectivo anual es de 27,71 %.
      .col-md-5.col-10.order-md-2.order-1.mb-md-0.mb-4
        figure.mb-5(data-aos="fade-left")
          img(src='@/assets/curso/temas/tema2/img08.png')
    
    .row.justify-content-center.BG01.p-4.mb-4(data-aos="fade-right")
      .col-md-3.col-10.mb-md-0.mb-4
        p.text-bold F:  $15.000.000
        p.text-bold n: 12 meses
        p.text-bold i: 27,71 % E.A.
      .col-md-6.col-10.mb-md-0.mb-4
        p El interés debe ser convertido a interés mensual debido a que los periodos se encuentran en meses, 1 año = 12 meses, por lo que en primer lugar se debe convertir la tasa efectiva anual a efectiva mensual:
      .col-md-3.col-10
        p.text-bold i =( 1 + 0,2771/12)<sup>12</sup>
        p.text-bold i = ( 1 + 0,023091666)<sup>12</sup>
        p.text-bold i = 1,315
    
    .row.justify-content-center.mb-4
      .col-md-6(data-aos="zoom-in")
        img.d-none.d-sm-none.d-md-block(src='@/assets/curso/temas/tema2/img09.svg')
        img.d-block.d-md-none(src='@/assets/curso/temas/tema2/img09b.svg')
    
    p Es decir, para que el inversionista cuente con $15.000.000 en un año a una tasa de interés de 1,1315 % efectiva mensual equivalente al 27,71 % efectivo anual, en un período de 12 meses debe invertir $12.823.266,57. Para comprobarlo se utiliza la fórmula de valor futuro.

    .row.justify-content-center.p-4.mb-4(data-aos="fade-right")
      .col-md-8.tarjeta.color-primario.p-4
        p.text-bold.text-center.mb-0 F = P(1 '+ i)<sup>n</sup>, F = 12'823.266,57(1 + 0,01315147813)<sup>12</sup>    = $15.000.000
    
    p Se puede comprobar que el cálculo estuvo bien ejecutado, pero es importante aclarar que la cifra en decimales debe tener la totalidad de números para obtener este resultado. Analice en el siguiente video cómo se pueden realizar estas conversiones y su aporte a las finanzas:

    figure.mb-5(data-aos="fade-right")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/D2nKQx9vSlE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

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
