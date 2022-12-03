<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Técnicas de priorización
    
    p La disponibilidad de recursos es uno de los factores de mayor complejidad a la hora de administrar una organización. Todo trabajo a llevar a cabo debe ser necesario para la generación de valor, que es el fin último de cualquier empresa; la lógica del costo de oportunidad, aplicable a prácticamente cualquier tarea sea o no del ámbito organizacional, indica que cada vez que se elige una alternativa entre varias se está renunciando a los beneficios de las demás. 
    p En muchas ocasiones, las empresas no cuentan con los recursos necesarios para implementar todas las estrategias que aporten a su crecimiento, por lo que se hace necesario tomar decisiones. Definir cuál es la opción más viable, bien sea porque es más provechosa, más fácil o rápida de implementar o más rentable, es una tarea que inevitablemente deja rezagadas a otras.

    .BGM01.px-md-5.px-4 
      .row.justify-content-center.align-items-center.mb-4
        .col-lg-1.d-none.d-lg-flex
          img(src='@/assets/curso/tema2/img02.svg')
        .col-lg-10.mb-4
          .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-4
            .bloque-texto-g__img(
              :style="{'background-image': `url(${require('@/assets/curso/tema2/img01.svg')})`}"
            )(data-aos="fade-right")
            .bloque-texto-g__texto.p-4(data-aos="fade-left")
              p.mb-0 La priorización es una metodología centrada en la presentación de tareas siguiendo un orden determinado, en la que a cada una de ellas se le otorga un nivel de importancia. De esta forma, el trabajo se puede realizar siguiendo la secuencia diseñada en función de estos criterios.
          p Priorizar resulta necesario e ineludible, pues las empresas no pueden contar con la totalidad de los recursos de capital, tiempo o personal para llevar a cabo todas las tareas de forma simultánea. Si existen 5 estrategias comerciales aplicables para mejorar los niveles de ventas, probablemente no habrá dinero suficiente para pagar todas las campañas publicitarias, ni vendedores o jefes de área que supervisen la evolución y el impacto; tampoco podría tenerse certeza de cuál de las estrategias es la más efectiva y está dando los mejores resultados.

      .row.justify-content-center.mb-4
        .col-lg-6.mb-lg-0.mb-4(data-aos="fade-right")
          p.mb-0 Por lo anterior, siempre la implementación de actividades se hace de forma lineal y no paralela, porque primero se debe corroborar la efectividad de una, antes de implementar la siguiente. Una vez se tiene certeza de lo apropiado de una medida, puede resultar conveniente probar otros métodos y, a través de un análisis comparativo, elegir aquella que sea más efectiva o proponer estrategias que las combinen para maximizar los resultados.
        .col-lg-6(data-aos="fade-left")
          p.mb-0 En la actualidad, existen diversas herramientas que funcionan como apoyo para la toma de esta clase de decisiones, al fin y al cabo aunque parezca un proceso intuitivo, estructurarlo con parámetros concretos puede dotarlo de mayor objetividad y minimizar la probabilidad de error. Los siguientes son algunos de los sistemas utilizados en la práctica:

      .row.justify-content-center.mb-5(data-aos="zoom-in")
        .col-lg-10
          img(src='@/assets/curso/tema2/img03.png')
    
    .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4
        img(src='@/assets/curso/temas/img01.svg' style="max-width: 32px;" data-aos="fade-right")
        h3.col.ps-3.mb-0.text-primario(data-aos="fade-left") Matriz de priorización

    p Esta herramienta corresponde a una tabla en la que se listan las opciones y cada uno de los criterios que apoyan o controvierten la elección de cada una de ellas. Funcionan de forma muy sencilla; pero, pueden aportar en la toma de decisiones. El objetivo es que al final se elija la opción que según los criterios dispuestos alcance mayor puntuación y se considere la más adecuada. Para utilizar este instrumento es importante tener claridad de los elementos clave y la forma en la que se debe proceder. Vea los pasos más relevantes:

    .row.justify-content-center.mb-4
      .col-lg-10.mb-4(data-aos="zoom-out")
        LineaTiempoD.color-acento-botones.mb-5
          .row(numero="1" titulo="Objetivo")
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img04.png')
            .col-lg-7
              .h4.text-primario Definir el objetivo
              p.mb-0 En primer lugar, debe tenerse claridad sobre lo que se busca potenciar, mitigar o solucionar. Las opciones para abordar esta situación solo pueden evaluarse, si primero se tiene claro lo que se espera alcanzar con su implementación.
          .row(numero="2" titulo="Alternativas")
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img05.png')
            .col-lg-7
              .h4.text-primario Listar las alternativas
              p.mb-0 Una vez se tiene claro qué se espera abordar se deben presentar las opciones disponibles; es aconsejable que el listado no sea tan extenso, puesto que puede dificultar el análisis posterior. Si el trabajo es en equipo, puede hacerse un filtro preliminar para que la matriz tenga únicamente las opciones más viables.
          .row(numero="3" titulo="Criterios")
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img06.png')
            .col-lg-7
              .h4.text-primario Determinar los criterios
              p.mb-0 Estos son los elementos de juicio que posteriormente sustentarán la elección de una opción, dependiendo del objetivo definido previamente, variarán los criterios a disponer, por ejemplo, si es una medida centrada en la generación de utilidades, algunos de los criterios más relevantes serán el costo de implementación, la certeza de la generación de utilidades y el volumen esperado de estas.
          .row(numero="4" titulo="Valor")
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img07.png')
            .col-lg-7
              .h4.text-primario Asignación de valor
              p.mb-0 En este paso se deben ponderar los criterios, lo que implica darles un nivel de importancia según la escala que defina el equipo. Qué tanto peso tiene un criterio sobre el consenso general, es un aspecto clave, pues implica que algunas alternativas en principio similares a otras puedan ser elegidas, debido a que resaltan en los criterios más relevantes.
          .row(numero="5" titulo="Comparar")
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img08.png')
            .col-lg-7
              .h4.text-primario Comparación de las alternativas
              p.mb-0 Para este punto se debe hacer un análisis de cada opción y puntuarlas en función de la ponderación previa; de esta manera se “califica” cada criterio otorgándole un valor, que puede ser comparado con los de otras opciones listadas.
          .row(numero="6" titulo="Opción")
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img09.png')
            .col-lg-7
              .h4.text-primario Elección de la opción
              p.mb-0 Una vez se han cuantificado todos los criterios, solo resta hacer la suma de todas las valoraciones obtenidas por cada alternativa y elegir aquella con el puntaje conjunto más elevado. De esta forma se conserva la objetividad, al dejar la elección condicionada a una operación aritmética. 
      .col-lg-10
        p.text-center Se presenta el siguiente ejemplo para comprender su aplicabilidad:
    
    figure.mb-4(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    p Existen otros sistemas de priorización utilizados; pero, su eje fundamental opera bajo el mismo sistema, es decir, determinar qué es lo más importante a través de una serie de criterios que contemplan tiempo, recursos, efectividad y esfuerzo. Vea esta breve reseña de algunos de ellos :

    .row.justify-content-center.mb-4(data-aos="zoom-in")
      TabsC.color-acento-botones
        .py-4.py-md-5(titulo="<b>Pirámide de priorización</b>")
          .row.justify-content-center
            .col-lg-7.order-lg-1.order-2.p-4
              p.mb-0 Una pirámide es una estructura con una base ancha, con mayor capacidad para contener actividades y soporta los niveles medio y superior, por lo que la priorización funciona en este sentido. En la cúspide se ubican las tareas o actividades más importantes que requieren especial atención; en el nivel intermedio aquellas que no se deben realizar tan pronto, pero que igual tienen importancia. En la base se ubican las tareas que no son imprescindibles y que, por lo tanto, si la situación durante el desarrollo de las demás fases lleva a ello, pueden ser dejadas a un lado en busca de la mayor efectividad con el menor costo. Cada nivel debe tener menos actividades que su inferior, de la misma forma, la prioridad será más alta según más arriba se encuentre ubicada. 
            .col-lg-3.col-6.order-lg-2.order-1.mb-lg-0.mb-4
              img(src="@/assets/curso/tema2/img10.png")
        .py-4.py-md-5(titulo="<b>Método RICE</b>")
          .row.justify-content-center
            .col-lg-7.order-lg-1.order-2.p-4
              p Por sus siglas en inglés que traducen alcance (R), impacto (I), confianza (C) y esfuerzo (E). Es un sistema que busca calcular a través de una fórmula sencilla el valor de un índice que determinará cuál actividad realizar. La fórmula en concreto es la siguiente:
              .row.justify-content-center.mb-4
                .col-lg-6.col-8 
                  img(src="@/assets/curso/tema2/img13.svg")
              p.mb-0 De la fórmula se desprende que se favorecerán las opciones con mayor alcance, impacto y confianza al menor esfuerzo. Así, a todas las propuestas se les deberá asignar un valor por cada elemento y efectuar el cálculo para determinar cuál tiene el índice más alto.
            .col-lg-3.col-6.order-lg-2.order-1.mb-lg-0.mb-4
              img(src="@/assets/curso/tema2/img11.png")
        .py-4.py-md-5(titulo="<b>Principio de Pareto</b>")
          .row.justify-content-center
            .col-lg-7.order-lg-1.order-2.p-4
              p Una máxima bastante popular en cualquier ámbito, el principio de Pareto indica que el 80% de los resultados provienen de un 20% del esfuerzo. Esto apunta a que en cualquier aspecto de la vida siempre habrá una proporción (cercana al 20%) de situaciones que motivan o desencadenan el 80% de las consecuencias. Para hacer uso de esta metodología, basta con listar las actividades o alternativas a desarrollar para una problemática concreta, se asigna un valor porcentual en función de algún criterio de medición (frecuencia, impacto, facilidad, beneficio asociado) y se lista de mayor a menor porcentaje. La suma total debe ser equivalente al 100% y debe prestarse especial atención a aquellas situaciones que en conjunto representan la mayor proporción de tal porcentaje. 
            .col-lg-3.col-6.order-lg-2.order-1.mb-lg-0.mb-4
              img(src="@/assets/curso/tema2/img12.png")

    p.text-center Observe el siguiente ejemplo para comprender mejor el principio de Pareto:

    .row.justify-content-center.mb-4
      .col-lg-10.BG03.p-md-5.p-4(data-aos="zoom-in")
        p Una empresa recibe quejas respecto a los productos que vende, actualmente cuenta con 2.000 solicitudes de devolución por los siguientes motivos:
        .BG02.mb-4
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-5.col-8.mb-lg-0.mb-4
              img(src="@/assets/curso/tema2/img14.svg")
            .col-lg-7.p-4
              ul.lista-ul--color
                li(style="margin-bottom: 3px")
                  <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
                  | Fallas en los productos: 300
                li(style="margin-bottom: 3px")
                  <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
                  |  Diferencias con lo mostrado en anuncios: 600
                li(style="margin-bottom: 3px")
                  <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
                  | Mala atención posventa: 800
                li(style="margin-bottom: 3px")
                  <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
                  | Deterioro acelerado durante los primeros meses de uso: 300
        p Se listan las causales de mayor a menor y se asigna el porcentaje de participación a cada uno de ellos, de igual forma, se presenta una columna en la que se vayan acumulando los porcentajes:
        .tabla-a.color-acento-botones.mb-5(data-aos="zoom-in")
          table
            thead(style="border-color: #DAE27F")
              tr
                th(style="background-color: #DAE27F; width: 40%").text-center Situación
                th(style="background-color: #DAE27F; width: 20%").text-center Frecuencia
                th(style="background-color: #DAE27F; width: 20%").text-center Participación
                th(style="background-color: #DAE27F; width: 20%").text-center Acumulado
            tbody
              tr
                td(style="background-color: #E8F2F6;").text-center.text-bold Mala atención posventa
                td(style="background-color: #E8F2F6;").text-center 800
                td(style="background-color: #E8F2F6;").text-center 40 %
                td(style="background-color: #E8F2F6;").text-center 40 %
              tr
                td(style="background-color: #fff;").text-center.text-bold Diferencias con anuncios
                td(style="background-color: #fff;").text-center 600
                td(style="background-color: #fff;").text-center 30 %
                td(style="background-color: #fff;").text-center 70 %
              tr
                td(style="background-color: #E8F2F6;").text-center.text-bold Fallas en los productos
                td(style="background-color: #E8F2F6;").text-center 300
                td(style="background-color: #E8F2F6;").text-center 15 %
                td(style="background-color: #E8F2F6;").text-center 85 %
              tr
                td(style="background-color: #fff;").text-center.text-bold Deterioro acelerado
                td(style="background-color: #fff;").text-center 300
                td(style="background-color: #fff;").text-center 15 %
                td(style="background-color: #fff;").text-center 100 %
              tr
                td(style="background-color: #E8F2F6;").text-center.text-bold Total
                td(style="background-color: #E8F2F6;").text-center 2.000
                td(style="background-color: #E8F2F6;").text-center 100 %
                td(style="background-color: #E8F2F6;").text-center
        p De la tabla anterior se interpreta que la mala atención después de la venta y la publicidad engañosa son las dos problemáticas que deben ser abordadas con mayor prioridad, puesto que concentran el 70 % de los reclamos efectuados por los clientes.

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
