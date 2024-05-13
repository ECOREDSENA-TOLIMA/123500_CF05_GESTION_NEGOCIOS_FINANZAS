<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Análisis financiero
    
    .row.justify-content-center.align-items-center.mb-4
      .col-md-7.col-10.order-md-1.order-2(data-aos="fade-right")
        p.mb-2 Es una técnica de diagnóstico organizacional por medio de la cual se analiza la estructura financiera de la empresa, en otras palabras, el sistema económico que ha construido la empresa a través de su trayectoria y en el medio al que pertenece, a partir de este estudio se puede tomar la empresa y dividirla en partes de acuerdo con su relevancia, para hacer comparaciones, las cuales orientan el quehacer de la organización y direcciona las decisiones a tomar de acuerdo con lo interpretado.<br><br>
        p.mb-0 Por este medio se conocen las tendencias en cuanto a decisiones financieras si se analizan varios periodos o vigencias, se determina el nivel de liquidez, así como el endeudamiento y el crecimiento del patrimonio en una organización en un periodo determinado, entre otros aspectos.
      .col-md-5.col-8.order-md-2.order-1.mb-md-0.mb-4
        figure.mb-5(data-aos="fade-left")
          img(src='@/assets/curso/temas/tema1/img01.png')
    
    p.mb-5 El análisis financiero se realiza con la utilización de tres instrumentos:
    
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-8.col-lg-6.col-12
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 <b>Figura 1. </b> <i>Tipos de análisis financiero</i>
        figure
          img(src='@/assets/curso/temas/tema1/img02.svg', alt='Imagen que menciona los tres instrumentos presentes en el análisis financiero, los cuales son: 1. El análisis vertical. 2. El análisis horizontal. 3. La aplicación de indicadores que varían.')  

    //- .row.justify-content-center.mb-4
    //-   .col-md-5.col-10(data-aos="zoom-in")
    //-     img(src='@/assets/curso/temas/tema1/img02.svg')
    
    p Desde los que permiten hallar la rentabilidad, pasando por el nivel de cuentas por cobrar, ventas y costos, hasta llegar a determinar la eficiencia de la organización mediante la aplicación de indicadores de actividad. 
    p Es de aclarar que cada uno de ellos arrojará cifras que requieren de una interpretación y que independientemente no dicen mucho, pero si se integran logran dilucidar grandes hallazgos acerca del presente y futuro de la organización; y es ahí donde está la habilidad de un analista financiero.
    p.mb-5 A continuación, se presentan los diferentes métodos utilizados para realizar análisis en una organización:

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-12
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 <b>Figura 2. </b> <i>Métodos de análisis</i>
        figure
          img.d-none.d-sm-none.d-md-block(src='@/assets/curso/temas/tema1/img03.svg', alt='En la figura 2 se presentan los diferentes métodos utilizados para realizar análisis en una organización')  
          img.d-block.d-md-none(src='@/assets/curso/temas/tema1/img03_1.svg', alt='En la figura 2 se presentan los diferentes métodos utilizados para realizar análisis en una organización') 
          figcaption Nota. Tomada de Calvo (2019).

      
    p.mb-5 El análisis financiero no tiene un procedimiento predeterminado, este se realiza teniendo en cuenta el cálculo de  los valores porcentuales y hallando la variación absoluta y relativa, para utilizar tantos indicadores como sea necesario, de esta manera se da a conocer las etapas para un análisis financiero:

    AcordionA.mb-5(tipo="a" clase-tarjeta="BG02")
      .row.justify-content-center(titulo="Etapa preliminar")
        .col-md-8.order-md-1.order-2
          p Primero debe informarse del tipo de usuario que requiere la información o a quién va dirigida, por esto es necesario conocer el objeto de este análisis, para definirlo se pueden encontrar tres circunstancias:
          ul.lista-ul--color
            li 
              i.fas.fa-check-circle
              | Bajo el supuesto que existe un problema en la empresa que debe ser solucionado, este debe ser claramente definido para que el analista sepa hacia dónde dirigir sus esfuerzos.
            li 
              i.fas.fa-check-circle
              | La empresa marcha con excelentes resultados, pero se espera prever cualquier situación de riesgo.
            li 
              i.fas.fa-check-circle
              | Estudiar si la empresa cuenta con la capacidad de absorber un mayor endeudamiento, este caso se presenta para entidades financieras al estudiar la aprobación de un crédito.
        .col-md-3.col-6.mb-md-0.mb-4.order-md-2.order-1
          img(src='@/assets/curso/temas/tema1/img04.svg')
      .row.justify-content-center(titulo="Etapa de estudio formal")
        .col-md-8.order-md-1.order-2
          p Esta etapa se considera la fase mecánica del análisis donde se recolecta la información de acuerdo con requerimientos y su disponibilidad. La información debe ser clasificada, agrupada de acuerdo con su relación, cuadros estadísticos, gráficos e índices, entre otros.
        .col-md-3.col-6.mb-md-0.mb-4.order-md-2.order-1
          img(src='@/assets/curso/temas/tema1/img05.svg')
      .row.justify-content-center(titulo="Etapa del análisis real")
        .col-md-8.order-md-1.order-2
          p En esta etapa se culmina el análisis de la información y se inicia la emisión de juicios mediante la metodología de comparación de índices y toda la información obtenida, clasificada y de los resultados obtenidos y da paso al proceso de relacionar la información o atar cabos para dar respuesta al interrogante que se espera resolver, se plantean alternativas de solución, se selecciona la más razonable y se inicia su implementación.
        .col-md-3.col-6.mb-md-0.mb-4.order-md-2.order-1
          img(src='@/assets/curso/temas/tema1/img06.svg')

    p.mb-4 Al llevar a cabo estas tres etapas propuestas en esta metodología, se disminuirá la posibilidad de emitir juicios erróneos y tomar decisiones desacertadas.

    //- .row.mb-4(data-aos="fade-right")
    //-   .col-auto.BG03.p-3
    //-     h4.mb-0 Método de porcientos integrales o análisis financiero vertical
        
    .h4.mb-4(data-aos="zoom-down-right")
      span.titulo-herramientas Método de porcientos integrales o análisis financiero vertical
    
    p Instrumento de diagnóstico organizacional que evidencia los grupos de interés, así como las políticas de la organización dentro de una vigencia.

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-12.col-lg-10
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 <b>Figura 3. </b> <i>Aspectos presentes en el análisis financiero vertical </i>
        figure
          img.d-none.d-sm-none.d-md-block(src='@/assets/curso/temas/tema1/fig03b.svg', alt='Imagen que menciona los aspectos que están presentes en el análisis financiero vertical. Destacando que en él se definen niveles de inventarios, realizan rubros y se hablan de pasivos, entre otros aspectos.')  
          img.d-block.d-md-none(src='@/assets/curso/temas/tema1/fig03a.svg', alt='Imagen que menciona los aspectos que están presentes en el análisis financiero vertical. Destacando que en él se definen niveles de inventarios, realizan rubros y se hablan de pasivos, entre otros aspectos.') 
          
    //- .row.justify-content-center.mb-5(data-aos="zoom-in")
    //-   .col-md-10
    //-     img(src='@/assets/curso/temas/tema1/img07.svg')
    
    .row.align-items-center.mb-4
      .col-md-5.col-10.mb-md-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/temas/tema1/img08.png')
      .col-md-7(data-aos="fade-left")
        p En este tipo de análisis financiero se encuentran las ventajas y desventajas que la organización posee al realizar un análisis con números relativos, su desventaja radica en que al realizar análisis en porcentajes se puede caer en errores si se pierde de vista el valor en pesos o en la moneda correspondiente.
        p A continuación, se presenta un ejemplo de este análisis donde se compara cada rubro con el total de su correspondencia, en efecto, se refiere a que se compara el efectivo con el total del activo circulante y el activo total, este parámetro debe ser definido para realizar el análisis y al presentar el informe de la interpretación de esta información:
    .row.justify-content-center.align-items-center.mb-5      
      .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
        p.mb-0 #[b Tabla 1.] #[em Métodos de porcientos o análisis vertical]
      
      .tabla-a.color-acento-contenido.mb-0(data-aos="fade-left")
        table
          thead
            tr
              td(colspan=6)(style="font-size: 18px; background-color: #3AE3FE;").text-center.text-bold Saloan 
                p.text-bold.mb-0 Estado de situación financiera del 1 de enero de 2021 a 31 de diciembre de 2021 
                p.text-bold valores en pesos ($)
          tbody    
            tr
              th(style="background-color: #F6F6F6;") Activo <br>Circulante
              th(style="background-color: #F6F6F6;").text-end 207.500.000,00 <br> 11.000.000
              th(style="background-color: #E1EFE3;").text-end 100,00 <br> 5,30
              th(style="background-color: #F6F6F6;") Pasivo <br>Corriente
              th(style="background-color: #F6F6F6;").text-end 114.500.000,00 <br>44.500.000
              th(style="background-color: #E8E8E8;").text-end 100,00 <br>38,86
            tr
              td Efectivo
              td.text-end 5.000.000
              td(style="background-color: #F3F9FF;").text-end 45,45
              td Obligaciones financieras
              td.text-end 25.000.000
              td(style="background-color: #E1FBFF;").text-end 56,18
            tr
              td Cuentas por cobrar
              td.text-end 3.500.000
              td(style="background-color: #F3F9FF;").text-end 31,82
              td Proveedores
              td.text-end 5.000.000
              td(style="background-color: #E1FBFF;").text-end 11,24
            tr
              td Inventario
              td.text-end 2.500.000
              td(style="background-color: #F3F9FF;").text-end 22,73
              td Acreedores
              td.text-end 12.000.000
              td(style="background-color: #E1FBFF;").text-end 26,97
            tr
              th Total activo circulante
              th
              th(style="background-color: #F3F9FF;").text-end 100,00
              td Pasivos por impuestos
              td.text-end 2.500.000
              td(style="background-color: #E1FBFF;").text-end 5,62
            tr
              td(colspan="3")
              th Total pasivo corriente
              th.text-end 44.500.000
              th(style="background-color: #E1FBFF;").text-end 100,00
            
            tr
              th(style="background-color: #F6F6F6;") Propiedad, planta y <br>equipo
              th(style="background-color: #F6F6F6;").text-end 196.500.000
              th(style="background-color: #E1EFE3;").text-end 94,70
              th(style="background-color: #F6F6F6;") Pasivo <br>no corriente
              th(style="background-color: #F6F6F6;").text-end 70.000.000
              th(style="background-color: #E8E8E8;").text-end 61,14
            tr
              td Terrenos
              td.text-end 76.000.000
              td(style="background-color: #E1FBFF;").text-end 38,68
              td Obligaciones financieras
              td.text-end 50.000.000
              td(style="background-color: #E1EFE3;").text-end 71,43
            tr
              td Edificios
              td.text-end 100.000.000
              td(style="background-color: #E1FBFF;").text-end 50,89
              td Dividendos por pagar
              td.text-end 20.000.000
              td(style="background-color: #E1EFE3;").text-end 28,57
            tr
              td Mobiliario
              td.text-end 23.000.000
              td(style="background-color: #E1FBFF;").text-end 11,70
              th Total pasivo corriente
              th.text-end 70.000.000
              th(style="background-color: #E1EFE3;").text-end 100,00
            tr
              td Inversiones
              td.text-end 9.500.000
              td(style="background-color: #E1FBFF;").text-end 4,83
              th(colspan="3")
            tr
              td Depreciación
              td.text-end 12.000.000
              td(style="background-color: #E1FBFF;").text-end -6,11
              th(style="background-color: #F6F6F6;") Patrimonio
              th.text-end(style="background-color: #F6F6F6;") 93.000.000,00 
              th.text-end(style="background-color: #F6F6F6;")
            tr
              td(colspan="2")
              td(style="background-color: #E1FBFF;").text-end 100,00
              th Capital
              th.text-end 24.000.000,00 
              th.text-end(style="background-color: #F3F9FF;") 25,81
            tr
              td(colspan="3")
              th Reservas legales
              th.text-end 4.000.000,00 
              th.text-end(style="background-color: #F3F9FF;") 4,30
            tr
              td(colspan="3")
              th Utilidad del ejercicio
              th.text-end 40.000.000,00 
              th.text-end(style="background-color: #F3F9FF;") 43,01
            tr
              td(colspan="3")
              th Utilidades acumuladas
              th.text-end 25.000.000,00 
              th.text-end(style="background-color: #F3F9FF;") 26,88
            tr
              td(colspan="3")
              td Total pasivo + patrimonio
              td.text-end 207.500.000,00  
              td.text-end(style="background-color: #F3F9FF;") 100,00

    .row.justify-content-center.mb-4
      .col-md-5.col-10.mb-md-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/temas/tema1/img09.png')
      .col-md-7(data-aos="fade-left")
        p Para realizar la operación o cálculos en el análisis vertical se debe tomar un factor o rubro base. Por ejemplo, para comparar el activo circulante y el no corriente o propiedad, planta y equipo se compara cada valor decir, el valor de $196.500.000 dividido entre el valor total del activo $207.500.000 arrojando un porcentaje de participación de 94,70 %, lo que indica que la empresa tiene una política fuerte de inversión en infraestructura para garantizar su actividad económica la cual requiere de una amplia y especializada infraestructura para su desarrollo.
        p Como se puede apreciar en el estado de situación financiera, se realizó el cálculo para realizar análisis parciales y totales, los cuales de acuerdo con su correspondencia se han sombreado con un color diferente, es así como el activo circulante se encuentra sombreado con color amarillo pero el análisis del activo circulante, junto con el valor del activo fijo y del total del activo, se encuentran con color verde. Se comprueba que el cálculo fue realizado correctamente cuando al sumar los porcentajes de cada rubro su resultado es igual a 1 si se utilizó decimales o a 100 % si se convirtió a porcentaje.

    p En el estado de situación financiera de Saloan al aplicar el método de porcientos, conocido como análisis vertical, y se puede concluir lo siguiente:

    TabsA.color-acento-botones.mb-5
      .tarjeta.color-acento-botones--borde.p-4(titulo="a) El circulante")
        .row.justify-content-center
          .col-md-5.col-10.mb-md-0.mb-4.order-md-1.order-2
            h4 El circulante
            p Solo ocupa el 5,30 % del total del activo.
          .col-md-5.col-8.mb-md-0.mb-4.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img10.png')
      .tarjeta.color-acento-botones--borde.p-4(titulo="b) El efectivo")
        .row.justify-content-center
          .col-md-5.col-10.mb-md-0.mb-4.order-md-1.order-2
            h4 El efectivo
            p Representa el 45,45 % del total del activo circulante por lo cual se puede deducir que la empresa esperaba asumir pronto un pago o realizar una inversión y prefirió que ese valor reposara en activo circulante al finalizar el año.
          .col-md-5.col-8.mb-md-0.mb-4.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img11.png')
      .tarjeta.color-acento-botones--borde.p-4(titulo="c) Las cuentas")
        .row.justify-content-center
          .col-md-5.col-10.mb-md-0.mb-4.order-md-1.order-2
            h4 Las cuentas
            p Por cobrar representan el 31,82 % del total de activo corriente o circulante, lo que permite deducir que la empresa maneja una política de ventas a crédito austera, de tal manera que su recuperación sea manejable y pronta.
          .col-md-5.col-8.mb-md-0.mb-4.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img12.png')
      .tarjeta.color-acento-botones--borde.p-4(titulo="d) En inventario")
        .row.justify-content-center
          .col-md-5.col-10.mb-md-0.mb-4.order-md-1.order-2
            h4 En inventario
            p La empresa ha destinado el 22,73 % del total del activo corriente lo que confirma la política previsiva en inversión de inventarios.
          .col-md-5.col-8.mb-md-0.mb-4.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img13.png')
      .tarjeta.color-acento-botones--borde.p-4(titulo="e) En activos fijos o propiedad")
        .row.justify-content-center
          .col-md-5.col-10.mb-md-0.mb-4.order-md-1.order-2
            h4 En activos fijos o propiedad
            p Planta y equipo los edificios cuentan con 50,89 % del total de estos activos lo cual permite deducir que la actividad económica de esta empresa debe requerir de una infraestructura apropiada y especial para su desempeño y seguido del terreno que está representado en 38,68 %, lo cual confirma la afirmación realizada.
          .col-md-5.col-8.mb-md-0.mb-4.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img14.png')
      .tarjeta.color-acento-botones--borde.p-4(titulo="f) El endeudamiento")
        .row.justify-content-center
          .col-md-5.col-10.mb-md-0.mb-4.order-md-1.order-2
            h4 El endeudamiento
            p Representa el 55,18 % de la sumatoria entre pasivo + patrimonio, esto indica que la empresa debe trabajar en su política de financiación, ya que este es superior al patrimonio de la empresa.
          .col-md-5.col-8.mb-md-0.mb-4.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img15.png')
      .tarjeta.color-acento-botones--borde.p-4(titulo="g) Sin acceder a más información")
        .row.justify-content-center
          .col-md-5.col-10.mb-md-0.mb-4.order-md-1.order-2
            h4 Sin acceder a más información
            p Que el estado de situación financiera se puede concluir que en esta sociedad su capital está representado por acciones por eso tiene una política de dividendos o beneficios a entregar a los inversionistas.
          .col-md-5.col-8.mb-md-0.mb-4.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img16.png')
      .tarjeta.color-acento-botones--borde.p-4(titulo="h) Se puede observar que")
        .row.justify-content-center
          .col-md-5.col-10.mb-md-0.mb-4.order-md-1.order-2
            h4 Se puede observar que la utilidad del ejercicio representa
            p El 43,01 % del patrimonio lo que devela que esta es una empresa productiva, aunque tiene un endeudamiento alto 71,43 % y el 56,18 % en obligaciones financieras a largo y corto plazo, genera utilidad y tiene el respaldo suficiente para cancelar sus obligaciones con entidades financieras que son las más costosas y riesgosas para la entidad. Y se podrían incluir muchas más dependiendo del criterio del analista financiero.
          .col-md-5.col-8.mb-md-0.mb-4.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img17.png')
    
    p En cuanto al estado de resultados o conocido como de ganancias y pérdidas el cálculo varía, porque hay un solo referente o punto focal siendo este las ventas, a partir de allí cada rubro se compara o se divide en las ventas obteniendo el porcentaje de participación de cada uno. En la siguiente tabla se presenta el Estado de Resultados y su análisis vertical:

    .row.justify-content-center.mb-4
      .col-lg-10.col-12
        .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
          p.mb-0 #[b Tabla 2.] #[em Método de porcientos en el estado de resultados] 
        
        .tabla-b.mb-0(data-aos="fade-left")
          table
            thead
              tr
                td(style="font-size: 18px; background-color: #3AE3FE;").text-center.text-bold Saloan 
                  p.text-bold.mb-0 Estado de situación financiera del 1 de enero de 2021 a 31 de diciembre de 2021 valores en pesos ($)
        table.mb-4(data-aos="fade-right")
          tr
            th(style="background-color: #F6F6F6;") Ventas
            th(style="background-color: #F6F6F6;").text-end 120.000.000,00 
            th(style="background-color: #F6F6F6;").text-end 100.00
          tr
            td Costo de ventas
            td.text-end 40.000.000 
            td(style="background-color: #EDF4EE;").text-end 33.33
          tr
            th(style="background-color: #F6F6F6;") Utilidad bruta
            th(style="background-color: #F6F6F6;").text-end 80.000.000 
            th(style="background-color: #EDF4EE;").text-end 66.67
          tr
            td Gastos de ventas
            td.text-end 8.505.000 
            td.text-end 7,09
          tr
            td(style="background-color: #F6F6F6;") Gastos de administración
            td(style="background-color: #F6F6F6;").text-end 11.800.000 
            td(style="background-color: #F6F6F6;").text-end 9,83
          tr
            th Utilidad operacional
            th.text-end 59.695.000 
            th.text-end 49,75
          tr
            td(style="background-color: #F6F6F6;") Otros ingresos
            td(style="background-color: #F6F6F6;").text-end 4.000.000 
            td(style="background-color: #F6F6F6;").text-end 3,33
          tr
            td Impuesto a la renta 35 %
            td.text-end 23.695.000 
            td.text-end 19,75
          tr
            th(style="background-color: #F6F6F6;") Utilidad neta
            th(style="background-color: #F6F6F6;").text-end 40.000.000 
            th(style="background-color: #EDF4EE;").text-end 33,33

    .row.align-items-center.BG01.p-4.mb-4
      .col-md-4.col-6.mb-md-0.mb-4
        img(src='@/assets/curso/temas/tema1/img18.png')
      .col-md-8
        p Para realizar el análisis vertical se debe tomar como base el valor total de las ventas equivalente al 100 % y a partir de allí cada uno de los conceptos aun los resultados correspondientes a utilidad bruta, operacional y neta también deben ser divididos entre el valor en pesos de las ventas, es decir, utilidad bruta / ventas x 100 = 80.000.000 / 120.000.000 x 100 = 66,67 %.
        p.mb-0 En el análisis de porcientos o vertical del estado de resultados de la empresa Saloan, se puede evidenciar que sus costos representan el 33,33 % de sus ventas generando una utilidad bruta del 66,67 % equivalente a $80.000.000, así mismo, los gastos en que incurre la empresa para garantizar su actividad representan el 16,92 % y el impuesto que asume la empresa equivale al 19.75 % erogaciones que representan el 36,67 %. Este último resultado de 36,67 %, sumado al 33,33 % de la utilidad neta y el 33,33 % correspondiente a los costos es igual al 103,33 % a este valor se le debe sustraer el 3,33 % equivalente a otros ingresos que ya están adicionados y esto arroja el 100 % de las ventas que corresponde a la comprobación de esta técnica el cual debe ser 100 %.

    
    .h4.mb-4(data-aos="zoom-down-right")
      span.titulo-herramientas Análisis financiero comparativo u horizontal

    .row.justify-content-center.align-items-center.mb-4
      .col-md-5.col-6.mb-md-0.mb-4(data-aos="fade-right")  
        img(src='@/assets/curso/temas/tema1/img19.png')
      .col-md-7(data-aos="fade-left")
        .BG05.p-4.mb-2
          p Este análisis se realiza para conocer la solidez de la empresa en cuanto a sus activos, patrimonio y respecto de las políticas organizacionales lo que se evidencia en las variaciones que se hallen por rubro y su incremento o decremento de un período a otro. Este análisis se realiza con los resultados financieros de, al menos, dos periodos o vigencias diferentes. 
          br
        .BG06.p-4.py-5.mb-2
          p Este análisis es dinámico gracias a que se enfoca en las modificaciones notorias que presentan los rubros de un periodo a otro. Es necesario anotar que este tiene en cuenta las variaciones absolutas o en pesos ($), así como las variaciones relativas o porcentuales (%).

    p Para realizar este análisis horizontal es necesario identificar el periodo o vigencia más reciente como “B”, el periodo anterior o más antiguo como “A”, la variación absoluta arrojará resultados en pesos ($) cuyo valor puede ser positivo si el rubro ha incrementado o negativo si el rubro ha disminuido. En cuanto a la variación relativa se refiere a (%) esta se calcula tomando la variación absoluta obtenida y dividiéndola en el valor en pesos correspondiente al mismo rubro en el año o vigencia anterior.

    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
      p.mb-0 #[b Tabla 3.] #[em Análisis horizontal]
    
    .tabla-a.color-acento-contenido.mb-0(data-aos="fade-left")
      table
        thead
          tr
            td(style="font-size: 18px; background-color: #3AE3FE;").text-center.text-bold Saloan 
              p.text-bold.mb-0 Estado de situación financiera del 1 de enero de 2020 al 31 de diciembre de 2021 valores en pesos ($)
    table.mb-4(data-aos="fade-right")
      tr
        th
        th 2020
        th 2021
        th VARIACIÓN ABSOLUTA
        th VARIACIÓN RELATIVA
      tr
        th
        th(style="background-color: #D2E1F1;") A
        th(style="background-color: #D2E1F1;") B
        th(style="background-color: #D2E1F1;") (B -A)
        th(style="background-color: #D2E1F1;") VA/A
      tr
        th(style="background-color: #F6F6F6;") Activo
        th(style="background-color: #F6F6F6;").text-end 201.700.000,00
        th(style="background-color: #F6F6F6;").text-end 207.500.000,00
        td(style="background-color: #F6F6F6;").text-end 5.800.000,00
        td(style="background-color: #F6F6F6;").text-end 2,88
      tr
        th Circulante
        th.text-end 11.200.000
        th.text-end 11.000.000
        td.text-end -200.000,00
        td.text-end 2,88
      tr
        td Efectivo
        td.text-end 1.000.000
        td.text-end 5.000.000
        td.text-end 4.000.000,00
        td(style="color: #F1592A;").text-end 400,00
      tr
        td Cuentas por cobrar
        td.text-end 5.700.000
        td.text-end 3.500.000
        td.text-end -2.200.000,00
        td.text-end -38,60
      tr
        td Inventario
        td.text-end 4.500.000
        td.text-end 2.500.000
        td.text-end -2.000.000,00
        td.text-end -44,44
      tr
        th(style="background-color: #F6F6F6;") Propiedad, planta y equipo
        th(style="background-color: #F6F6F6;").text-end 190.500.000,00
        th(style="background-color: #F6F6F6;").text-end 196.500.000,00
        td(style="background-color: #F6F6F6;").text-end 6.000.000,00
        td(style="background-color: #F6F6F6;").text-end 3,15
      tr
        td Terrenos
        td.text-end 76.000.000
        td.text-end 76.000.000
        td.text-end -
        td.text-end 0,00
      tr
        td Edificios
        td.text-end 100.000.000
        td.text-end 100.000.000
        td.text-end -
        td.text-end 0,00
      tr
        td Mobiliario
        td.text-end 23.000.000
        td.text-end 23.000.000
        td.text-end -
        td.text-end 0,00
      tr
        td Inversiones
        td.text-end 3.500.000
        td.text-end 9.500.000
        td.text-end 6.000.000,00
        td(style="color: #F1592A;").text-end 171,43
      tr
        th(style="background-color: #F6F6F6;") Pasivo
        th(style="background-color: #F6F6F6;").text-end 147.700.000,00
        th(style="background-color: #F6F6F6;").text-end 114.500.000,00
        td(style="background-color: #F6F6F6;").text-end -33.200.000,00
        td(style="background-color: #F6F6F6;").text-end -22,48
      tr
        th Corriente
        th.text-end 57.700.000
        th.text-end 4.500.000
        td.text-end -13.200.000,00
        td.text-end -22,88
      tr
        td Obligaciones financieras
        td.text-end 27.200.000
        td.text-end 25.000.000
        td.text-end -2.200.000,00
        td.text-end -8,09
      tr
        td Proveedores
        td.text-end 10.000.000
        td.text-end 5.000.000
        td.text-end -5.000.000,00
        td.text-end -50,00
      tr
        td Acreedores
        td.text-end 18.000.000
        td.text-end 12.000.000
        td.text-end -6.000.000,00
        td.text-end -33,33
      tr
        td Pasivos por impuestos
        td.text-end 2.500.000
        td.text-end 2.500.000
        td.text-end -
        td.text-end 0,00
      tr
        th(style="background-color: #F6F6F6;") Pasivo no corriente
        th(style="background-color: #F6F6F6;").text-end 90.000.000,00
        th(style="background-color: #F6F6F6;").text-end 70.000.000,00
        td(style="background-color: #F6F6F6;").text-end -20.000.000,00
        td(style="background-color: #F6F6F6;").text-end -22,22
      tr
        td Obligaciones financieras
        td.text-end 70.000.000
        td.text-end 50.000.000
        td.text-end -20.000.000,00
        td.text-end -28,57
      tr
        td Dividendos por pagar
        td.text-end 20.000.000
        td.text-end 20.000.000
        td.text-end -
        td.text-end 0,00
      tr
        th(style="background-color: #F6F6F6;") Patrimonio
        th(style="background-color: #F6F6F6;").text-end 54.000.000,00
        th(style="background-color: #F6F6F6;").text-end 93.000.000,00
        td(style="background-color: #F6F6F6;").text-end 39.000.000,00
        td(style="background-color: #F6F6F6;").text-end 72,22
      tr
        td Capital
        td.text-end 30.000.000
        td.text-end 24.000.000
        td.text-end -6.000.000,00
        td.text-end -20,00
      tr
        td Reservas legales
        td.text-end 4.000.000
        td.text-end 4.000.000
        td.text-end -
        td.text-end 0,00
      tr
        td Utilidad del ejercicio
        td.text-end -5.000.000
        td.text-end 40.000.000
        td.text-end 35.000.000,00
        td(style="color: #F1592A;").text-end 700,00
      tr
        td Utilidades acumuladas
        td.text-end 25.000.000
        td.text-end 25.000.000
        td.text-end -
        td.text-end 0,00
      tr
        th(style="background-color: #F6F6F6;") Pasivo + patrimonio
        th(style="background-color: #F6F6F6;").text-end 201.700.000,00
        th(style="background-color: #F6F6F6;").text-end 207.500.000,00
        td(style="background-color: #F6F6F6;" colspan="2")
    
    p De esta manera, se realiza el cálculo para obtener variaciones absolutas y relativas y se puede concluir lo siguiente:

    PasosA.color-acento-contenido.mb-5(tipo="l")
      .row.justify-content-center.align-items-center
        .col-md-6.col-10.order-md-1.order-2
          p Se evidencia un incremento de 400 % en efectivo, lo que corrobora la conclusión planteada en el análisis vertical, donde se específica que la empresa debe tener un compromiso próximo a cumplir, razón por la que se prefiere dejar en caja un valor que, finalizando año, podría ser invertido para obtener mayores beneficios.
        .col-md-4.col-8.order-md-2.order-1.mb-md-0.mb-4(data-aos="fade-left")
          img(src='@/assets/curso/temas/tema1/img20.png')
      .row.justify-content-center.align-items-center
        .col-md-4.col-8.mb-md-0.mb-4(data-aos="fade-right")
          img(src='@/assets/curso/temas/tema1/img21.png')
        .col-md-6.col-10
          p Se evidencia un incremento de 171,3 % en inversiones en el año 2021, lo que se define como una política de inversión con el fin de obtener mejores beneficios para recuperar en algún % los efectos de la Covid-19 en el 2020.
      .row.justify-content-center.align-items-center
        .col-md-6.col-10.order-md-1.order-2
          p Se refleja un incremento de 700 % en la utilidad del ejercicio, lo que evidencia que a pesar de la situación la empresa se ha enfocado en trabajar fuertemente por recuperar su nivel de productividad y, por ende, de generar utilidad. 
        .col-md-4.col-8.order-md-2.order-1.mb-md-0.mb-4(data-aos="fade-left")
          img(src='@/assets/curso/temas/tema1/img22.png')
      .row.justify-content-center.align-items-center
        .col-md-4.col-8.mb-md-0.mb-4(data-aos="fade-right")
          img(src='@/assets/curso/temas/tema1/img23.png')
        .col-md-6.col-10
          p La empresa ha trabajado en disminuir sus compromisos con entidades financieras, proveedores y acreedores tanto a corto como a largo plazo lo cual demuestra la habilidad de la gerencia para dirigir la empresa y la cohesión de su equipo de trabajo para aunar esfuerzos y alcanzar objetivos.      
      
    
    .h4.mb-4(data-aos="zoom-down-right")
      span.titulo-herramientas Análisis financiero integral
    
    p El análisis financiero lleva consigo un gran peso de importancia, pues a partir de su implementación se determinan los efectos de posibles decisiones de inversión, de la implementación de políticas de inversión y mercantiles como margen de utilidad, precio, promoción y publicidad, cobertura geográfica, colocación; de lineamiento de desarrollo de procesos y productos, retribuciones y medios de financiación. Es así como se comparten los elementos que deben integrar el análisis financiero integral. 


    .row.justify-content-center.align-items-center.mb-4.BG01
      .col-md-12.p-3
        SlyderA(tipo="b")
          .row.justify-content-center.BG01.p-4
            .col-md-7
              h4 El análisis financiero integral 
              p Es una herramienta poderosa que permite conocer la posición presente y futura de una organización sumado a los resultados de sus operaciones como base fundamental para proyectar las predicciones y estimaciones posibles sobre las condiciones y resultados futuros.
            .col-md-5
              figure
                img(src="@/assets/curso/temas/tema1/img28_1.png", alt="Imagen decorativa")
          .row.justify-content-center.BG01.p-4
            .col-md-7
              h4 Analista como financiero integral  
              p Para que un analista sea experto y tenga un desempeño extraordinario necesita, indefectiblemente, tener un sólido conocimiento contable y dominar las técnicas de análisis financiero que facilitan la identificación y relación entre diferentes factores o rubros financieros y operativos.
            .col-md-5
              figure
                img(src="@/assets/curso/temas/tema1/img28_2.png", alt="Imagen decorativa")
          .row.justify-content-center.BG01.p-4
            .col-md-7
              h4 Estado de fuente y aplicación de fondos 
              p Entre ellas se encuentra el Estado de Fuente y Aplicación de Fondos (EFAF) o también conocido como estado de fuentes y usos, estado de cambios en la posición financiera o estado de movimiento de fondos.
            .col-md-5
              figure
                img(src="@/assets/curso/temas/tema1/img28_3.png", alt="Imagen decorativa")
          .row.justify-content-center.BG01.p-4
            .col-md-7
              h4 EFAF 
              p Evidencia a través de qué rubro, actividad específica o fuentes de dónde provinieron los recursos que la organización obtuvo durante un periodo y el uso o aplicación de ellos que difiere del Estado de Flujo de Efectivo (EFE), ya que este solo se expresa en términos monetarios.
            .col-md-5
              figure
                img(src="@/assets/curso/temas/tema1/img28_4.png", alt="Imagen decorativa")
          .row.justify-content-center.BG01.p-4
            .col-md-7
              h4 Disponibilidad de recursos 
              p Menciona fondos para referirse a la disponibilidad constante de recursos para garantizar la operatividad de la empresa donde el efectivo solo es uno de tantos recursos, ya que un movimiento de fondos puede y no implicar una transferencia de efectivo.
            .col-md-5
              figure
                img(src="@/assets/curso/temas/tema1/img28_5.png", alt="Imagen decorativa")

    .row.justify-content-center.align-items-center.mb-4
      .col-md-7.col-10.mb-md-0.mb-4.order-md-1.order-2
        p Sin embargo, se asimilan en que permiten evaluar la calidad o pertinencia de las decisiones gerenciales lo que puede definirse al evaluar la “Generación Interna de Fondos - GIF” conocida también como recursos o fondos propios que llevan ese nombre porque son producidos directamente en la actividad económica generando las posibilidades de crecimiento, pago de dividendos y recuperación económica y se halla así:
        .BG07.p-4
          .BG08.p-2
            p.text-bold Utilidad neta + Depreciación del período + Amortizaciones diferidas del periodo = GIF
      .col-md-3.col-6.order-md-2.order-1(data-aos="fade-left")
        img(src='@/assets/curso/temas/tema1/img25.svg')

    p La calidad de las decisiones gerenciales relacionadas con EFAF están orientadas a realizar una eficiente gestión de los recursos que tienen una directriz y es que los fondos de corto plazo se deben aplicar o utilizar en usos de corto plazo y los fondos de largo plazo debieran financiar las aplicaciones de largo plazo.
    p También existe el EFAF con base en los cambios en el capital de trabajo que se dedica a expresar el aumento o disminución en el capital de trabajo, que radica su limitación en la fórmula para calcular el capital de trabajo:

    .row.justify-content-center.mb-4
      .col-lg-7
        img(src='@/assets/curso/temas/tema1/img26.svg')

    p Este indicador permite hallar la disminución o riesgo que tiene la empresa de utilizar los recursos en actividades diferentes a la operación del negocio lo que conduce a arriesgar la operatividad de la empresa y su trayectoria en el tiempo.

    separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1. Revelaciones
    
    .row.justify-content-center.align-items-center.mb-4
      .col-md-7.col-10.mb-md-0.mb-4.order-md-1.order-2
        p Las revelaciones son la información o explicación que se presenta en las notas a los estados financieros las cuales son señales, se deben presentar de manera ordenada, secuencial, congruente conforme se presenta la información financiera. Corresponden a comentarios que se incluyen en los estados financieros de una organización para ampliar información acerca de datos específicos que presentan estos informes.
        p Su función es brindar información comprensible que devele, entre otras, el fundamento para elaborar los estados financieros, políticas contables, de cartera, de proveedores, de inversiones y todas las que sea necesario precisar para brindar una información clara, verídica y completa, así como la información que no fue incluida en los estados financieros, además de las prácticas contables y todo lo que sea necesario para aportar a las decisiones de tipo económico.
      .col-md-5.col-8.order-md-2.order-1(data-aos="fade-left")
        img(src='@/assets/curso/temas/tema1/img27.png')
    
    .row.justify-content-center.align-items-center.mb-4
      .col-md-5.col-8(data-aos="fade-left")
        img(src='@/assets/curso/temas/tema1/img28.svg')
      .col-md-7.col-10.mb-md-0.mb-4
        p Estas son notas o narraciones que deben ser claras y concretas, estar numeradas o claramente identificadas en orden secuencial. Las notas, son parte integral de todos y cada uno de los estados financieros, partidas extraordinarias, primas de descuentos causados pendientes de amortizar. La información suministrada debe cumplir con el fundamento de la información financiera, las descripciones de esta deben ser útiles, gracias a su concepción, identificación y valuación de los componentes de los estados financieros, y en especial del capital y su protección.
        p Las revelaciones cobran vital importancia en la gestión financiera gracias a que influyen en la toma de decisiones por las partes interesadas de la información tomando un carácter predictivo, confirmatorio o ambos. Pero la descripción o inclusión inapropiada de la información financiera y sus revelaciones pueden influir en decisiones erróneas por parte de los usuarios de la información.

    .h4 Criterios para realizar revelaciones de los estados financieros
    p Los criterios para definir la información a revelar en los estados financieros deben estar ordenados y clasificados según:
    
    .row.justify-content-center.mb-4
      .col-md-11
        ul.lista-ul
          li 
            <i class="fas fa-folder-open fa-fw" style="color:#6DEBFF"></i>
            | Los activos y pasivos más importantes de acuerdo con el uso que se destinan, la exigibilidad o liquidación, término de tiempo y valores.
          li 
            <i class="fas fa-folder-open fa-fw" style="color:#6DEBFF"></i>
            |La fecha de corte o periodo al cual pertenecen.
          li 
            <i class="fas fa-folder-open fa-fw" style="color:#6DEBFF"></i>
            |	Principales prácticas y políticas contables con énfasis en las modificaciones contables que hubiesen ocurrido.
          li 
            <i class="fas fa-folder-open fa-fw" style="color:#6DEBFF"></i>
            |	Los ingresos y gastos principales.
          li 
            <i class="fas fa-folder-open fa-fw" style="color:#6DEBFF"></i>
            |	Los activos y pasivos descontados que sean objeto de devolución o compensación, al igual que las garantías y contingencias.
          li 
            <i class="fas fa-folder-open fa-fw" style="color:#6DEBFF"></i>
            |	Errores de vigencias anteriores.

    separador
    #t_1_2.titulo-segundo.color-acento-contenido.ms-5(data-aos="fade-right")
      h2 1.2. Indicadores financieros       
    
    .row.justify-content-center.align-items-center.mb-5
      .col-md-5.col-8(data-aos="fade-left")
        img(src='@/assets/curso/temas/tema1/img29.png')
      .col-md-7.col-10.mb-md-0.mb-4
        p Los indicadores financieros son instrumentos que facilitan el análisis financiero al comparar datos diferentes lo que hace que también se les conozca como razones financieras, por medio de ellos se identifican puntos fuertes y débiles de la empresa y comparados con periodos o resultados anteriores permiten determinar probabilidades y tendencias. Aportan a realizar una comparación lógica; es decir, dentro de datos que tengan relación o que cuenten con las mismas características, lo que daría lugar a realizar comparaciones para determinar su incremento, variación, decremento y el impacto que estas han generado en la organización.
        p A continuación, se realiza una presentación generalizada de estos indicadores, los cuales cumplen una función específica y permiten realizar hallazgos determinantes para la organización:
    
    .BG01.p-4.mb-5(data-aos="fade-right")
      SlyderA(tipo="b")
        .row.justify-content-center
          .col-md-5.col-10.p-0.px-0.order-md-1.order-2          
            h4.mb-0.mx-4 Indicadores de liquidez
            p.mx-4 Razón corriente, capital neto de trabajo y prueba ácida son indicadores que en conjunto permiten evaluar la capacidad de la organización para pagar sus compromisos y obligaciones de corto plazo.
          .col-md-5.col-10.px-0.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img30.png')
        .row.justify-content-center
          .col-md-5.col-10.p-0.px-0.order-md-1.order-2
            .BG01.p-2.mb-4
              h4.mb-0.mx-4 Indicadores de actividad
            p.mx-4 En los Indicadores de actividad se tienen rotación de cartera, periodo promedio de cobro, descuento por pronto pago, rotación de inventarios, rotación de inventarios para empresas comerciales, rotación de inventarios para empresas industriales y ciclo de efectivo
            p.mx-4.mb-0 La rotación de proveedores consiste en evaluar el número de días que la empresa toma para pagar a los proveedores, es decir, el número de días que los proveedores aportan a la financiación de la empresa.
          .col-md-5.col-10.px-0.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img31.png')
        .row.justify-content-center
          .col-md-5.col-10.p-0.px-0.order-md-1.order-2
            .BG01.p-2.mb-4
              h4.mb-0.mx-4 Indicadores de rentabilidad
            p.mx-4 Conocidos también como indicadores de rendimiento, son útiles para evaluar la efectividad de la administración de la organización y controlar la inversión en la actividad económica y los egresos generados por la misma, así como su efectividad para convertirlos en ventas. En este grupo se encuentran margen bruto, margen operacional, margen neto, rendimiento del patrimonio, rendimiento del activo total, Ebitda y sistema Dupont.
          .col-md-5.col-10.px-0.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img32.png')
        .row.justify-content-center
          .col-md-5.col-10.p-0.px-0.order-md-1.order-2
            .BG01.p-2.mb-4
              h4.mb-0.mx-4 Indicadores de endeudamiento
            p.mx-4 Son instrumentos que permiten evaluar el grado y en qué forma participan los acreedores en la financiación de la organización, y de esta manera conocer el riesgo de los inversionistas y la pertinencia de un endeudamiento. En este rango se encuentran los indicadores de crisis, a saber:
          .col-md-5.col-10.px-0.order-md-2.order-1
            .titulo-sexto.color-acento-contenido.mb-4
              h5 Tabla 4.
              em Indicadores de crisis
            table
              caption Fuente: (Ortiz, 2018)
              tr
                th(style="background-color: #FCC15A;") Indicador
                th(style="background-color: #FCC15A;") Parámetro
              tr
                td(style="background-color: #FFF;") Endeudamiento financiero
                td.text-center(style="background-color: #FFF;") &lt; 30 %
              tr
                td(style="background-color: #F6F6F6;") Impacto de la carga financiera
                td.text-center(style="background-color: #F6F6F6;") &lt; 10 %
              tr
                td(style="background-color: #FFF;") Cobertura de intereses
                td.text-center(style="background-color: #FFF;") &#8805; 1 vez

        .row.justify-content-center
          .col-md-5.col-10.p-0.px-0.order-md-1.order-2
            .BG01.p-2.mb-4
              h4.mb-0.mx-4 Indicadores de Leverage
            p.mx-4 Estos indicadores también conocidos como de apalancamiento comparan el financiamiento procedente de terceros con la inversión de los socios para determinar cuál de los dos grupos está corriendo el mayor riesgo. En este grupo se encuentran los indicadores Leverage total y Leverage a corto plazo.
          .col-md-5.col-10.px-0.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img34.png')
        .row.justify-content-center
          .col-md-5.col-10.p-0.px-0.order-md-1.order-2
            .BG01.p-2.mb-4
              h4.mb-0.mx-4 Indicadores de apalancamiento
            p.mx-4 El apalancamiento en el entorno organizacional es una estrategia gerencial que facilita la reducción de costos con el fin de lograr una mayor rentabilidad de manera que esta sea superior a las utilidades obtenidas con el capital propio. Existe el apalancamiento operativo o GAO, el apalancamiento financiero GAF y el apalancamiento total GAT.
          .col-md-5.col-10.px-0.order-md-2.order-1
            img(src='@/assets/curso/temas/tema1/img35.png')

    .row.justify-content-center.mb-4
      .col-md-8.p-4
        .row.justify-content-center.align-items-center(style="background-color:#03386E;border-radius:10px")
          .col-md-2.col-3.mb-md-0.mb-4
            img(src='@/assets/curso/temas/tema1/img36.png')
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0
                p(style="color:white") Ahora, veamos representados los indicadores consolidados, para ello haz clic en el botón Descargar. 
              .col-sm-auto
                a.boton.color-acento-botones(:href="obtenerLink('downloads/Indicadores_financieros.pdf')" target="_blank")
                  span Descargar
                  i.fas.fa-file-download

    .cajon.color-secundario.p-4.mb-4(style="background-color:#E1EFE3")
      p Los indicadores son instrumentos efectivos que aportan al análisis financiero de la organización, pero individualmente es poco su aporte, por esa razón es necesario establecer parámetros de comparación los cuales deben estar apoyados en el criterio del analista, tener en cuenta que los indicadores deben ser resultados de la misma empresa, de periodos anteriores y también pueden compararse con indicadores promedio de la industria a la que pertenece la organización.

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({}),
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
