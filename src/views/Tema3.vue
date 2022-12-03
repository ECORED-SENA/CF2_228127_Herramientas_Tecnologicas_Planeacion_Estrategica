<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Informes
    
    p Una vez se han ejecutado las tareas propuestas se debe dar conclusión a las actividades a través de un reporte que presente de forma resumida la problemática, los planes de acción y los resultados alcanzados. Este documento conocido como informe funciona consolidando todos los aspectos relevantes para ser evaluado por los usuarios interesados.

    .BG04.mb-4(data-aos="flip-up")
      .row.justify-content-center.align-items-end.mb-4
        .col-lg-3.col-6.mb-lg-0.mb-4.order-1
          img(src="@/assets/curso/tema3/img01.png")
        .col-lg-8.p-4.order-lg-2.order-3
          p Esta fase cierra el ciclo de la información, que inició con la recolección de datos, seguido de su análisis y conservación y finaliza con la generación de conclusiones, que llevarán a determinar un camino a seguir, bien sea implementando medidas correctivas o soportando la continuidad de las actividades que se consideren exitosas.
          p.mb-0 Los informes funcionan como compilatorios de todos los eventos y hechos relevantes que se dieron durante la operación de la empresa, aportando respuesta a los interrogantes que motivaron el trabajo, y concluyen con los resultados y las recomendaciones que de allí se derivan.
        .col-lg-1.col-2.order-lg-3.order-2
          img(src="@/assets/curso/tema3/img02.svg")

    .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4
        img(src='@/assets/curso/temas/img01.svg' style="max-width: 32px;" data-aos="fade-right")
        h3.col.ps-3.mb-0.text-primario(data-aos="fade-left") Tipos
    
    p La clasificación de los informes varía en función de los criterios utilizados, a continuación se presentan aquellos de mayor aplicación: 

    .row.justify-content-center.mb-5(data-aos="zoom-in")
      .col-lg-10.mb-4
        .titulo-sexto.color-acento-contenido.mb-4
          h5 Figura 2
          span Tipos de informes
        ImagenInfografica.color-acento-botones
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema3/img03.svg')
          .BG05.p-3(x="36%" y="41.5%" numero="+")
            p.mb-0 Es un documento conciso cuya extensión no supera las 10 páginas. Puede funcionar como resumen de un informe largo; su propósito es presentar la mayor cantidad de información relevante en una breve cantidad de páginas. Se utiliza en ámbitos corporativos de alto nivel, por ejemplo, en juntas directivas, donde se les informa a los participantes de mayor rango, los aspectos importantes de la ejecución administrativa, para sustentar la posterior toma de decisiones. 
          .BG05.p-3(x="36%" y="58%" numero="+")
            p.mb-0 Su extensión supera las 10 páginas y no cuentan con un límite definido, por lo que el autor puede detallar todas las situaciones evidenciadas. Es el tipo de informe idóneo para problemáticas muy complejas o que comprenden muchas ideas útiles para el lector.
          .BG05.p-3(x="64%" y="41.5%" numero="+")
            p.mb-0 Este tipo de informe se dirigen al público en general, presentan temáticas de amplio espectro y entendimiento por la población. Tienen un lenguaje sencillo para facilitar la comprensión de los lectores.
          .BG05.p-3(x="64%" y="58%" numero="+")
            p.mb-0 Documentos más complejos que demandan conocimiento previo en la disciplina que abordan. Generalmente, presentan tecnicismos que limitan el entendimiento a un nicho concreto de lectores, usualmente son el resultado de trabajos de investigación.
          .BG05.p-3(x="64%" y="74%" numero="+")
            p.mb-0 Se centran en temáticas específicas asociadas a una problemática. Es uno de los más utilizados en el contexto administrativo, puesto que facilita la implementación de comparativas a partir de escenarios, lo que aporta para la toma de decisiones.
          .BG05.p-3(x="64%" y="90.5%" numero="+")
            p.mb-0 Funciona como un punto intermedio entre un informe técnico y uno divulgativo. Se abordan temáticas específicas, pero dirigidas a un público más amplio, por lo cual se trata de simplificar aspectos no tan relevantes para facilitar el entendimiento.

    .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4
        img(src='@/assets/curso/temas/img01.svg' style="max-width: 32px;" data-aos="fade-right")
        h3.col.ps-3.mb-0.text-primario(data-aos="fade-left") Estructura según las normas técnicas
    
    p Los informes, al ser un documento de especial atención, deben cumplir con una serie de requerimientos para facilitar la comprensión y aprovechamiento de la información que en ellos se dispone. Se presentan dos de las normativas técnicas más utilizadas en Colombia:

    .tarjeta--container.row.mb-4
      .col-md.BGR04A.p-5(data-aos="fade-right")
        .row.justify-content-center.mb-4
          .col-4
            img(src='@/assets/curso/tema3/img04.svg')
        .h4 Estructura bajo las Normas APA
        p.mb-0 Las Normas APA son un estándar creado por la Asociación de Psicólogos Americanos o APA por sus siglas en inglés, centrado en el establecimiento de lineamientos específicos para la producción de documentos escritos a nivel internacional. Su uso es de amplio espectro cubriendo desde trabajos académicos, de investigación o de naturaleza económica. Actualmente, cuentan con una gran popularidad por lo que son consideradas como el marco más utilizado en una gran porción de los sectores académicos, económicos y sociales alrededor del mundo. En su manual de aplicación se detallan las características específicas de cada uno de los apartados del documento, lo que incluye portada, resumen, introducción, resultados, citas, referencias, entre otros.
      .col-md.BGR03A.p-5(data-aos="fade-left")
        .row.justify-content-center.mb-4
          .col-4
            img(src='@/assets/curso/tema3/img05.svg')
        .h4 Estructura bajo la Norma Técnica de Calidad (NTC 1486)
        p Al igual que en el caso anterior, se centra en las reglas para la presentación de trabajos escritos, tiene especial énfasis en trabajos de investigación y académicos; pero puede ser utilizada en cualquier ámbito. Son emitidas por el Instituto Colombiano de Normas Técnicas y Certificación – ICONTEC.
        p.mb-0 Cada una de las secciones que comprende el informe tiene su propio apartado dentro de la norma técnica, lo que permite ser específico y preciso en su presentación. Algunos apartados allí descritos son la tapa, la portada, las listas especiales, el glosario, el resumen, la introducción, el capítulo, las conclusiones, las recomendaciones, la bibliografía, los índices, los anexos, entre otros. 

    .row.justify-content-center.mb-4
      .col-lg-10.mb-5
        .BGR08.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/img02.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  .h4.text-white Normas APA - ICONTEC
                  p.text-white.mb-0 Para conocer algunas de las generalidades de las Normas APA e ICONTEC se invita a consultar el siguiente PDF. 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/cuadro_comparativo.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
      .col-lg-10
        p La elección de un sistema u otro dependerá de lo que se busca con la presentación del informe y el tipo de público al que va dirigido. En algunas ocasiones es exigencia de los superiores el uso del uno o del otro; sin embargo, cada uno tiene un enfoque que lo hace más viable según el escenario que se espera trasladar al documento.
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/tema3/img06.png')


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
