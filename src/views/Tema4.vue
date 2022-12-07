<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Catálogo de servicios de TI
    
    p Las organizaciones, empresas o compañías de cualquier sector económico han depositado su confianza en los servicios de TI, toda vez que facilitan la creación de valor y proporcionan una ventaja competitiva. Es por eso que la pandemia y la postpandemia generada por el COVID 19 abren una oportunidad para que se creen y utilicen nuevos servicios orientados a la productividad y a la innovación de las tareas. En ese sentido, a medida que crece la transformación digital, los servicios deben ser usables para que los usuarios finales o clientes puedan acceder a una interfaz organizada y de fácil acceso que incluya la documentación idónea.  Entonces, <span style="color=#3185AF">#[b ¿qué se ocasiona si no se generan buenas prácticas a nivel empresarial?]</span>
    p Si no se generan buenas prácticas en la presentación de los servicios tecnológicos a los usuarios finales, ya sea por falta de una interfaz completa o por simple logística y organización de la empresa, se presentará un riesgo que afectará los desempeños. 

    .row.justify-content-center.mb-4
      .col-lg-10.mb-4
        .bloque-texto-g.color-primario.bloque-inv.p-3.p-sm-4.p-md-5.mb-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema4/img01.jpg')})`}"
          )(data-aos="fade-left")
          .bloque-texto-g__texto.p-4(data-aos="fade-right")
            .h4.text-primario ¿Cuál es el riesgo?
            p.mb-0 Que la cantidad de solicitudes que lleguen a la mesa de servicios de TI no puedan ser atendidas, además que lleguen solicitudes que exigen más información sobre las ofertas de servicios. Por ello, la carga operativa que recae sobre los técnicos de TI se elevará y no se les permitirá enfocarse en otras funciones críticas de TI.

      .col-lg-3.col-6.mb-lg-0.mb-4
        img(src="@/assets/curso/tema4/img02.svg")
      .col-lg-7.mb-4
        p De esta manera, las divisiones de tecnología tienen un papel muy importante no solo para generar la estabilidad de infraestructura tecnológica, sino que se vuelven un eje estratégico en la misión y visión de las compañías.
        p Entonces, comprenda qué es y cómo se compone un catálogo de servicios y sus beneficios acerca de este concepto. 
        p.mb-0 Primero, entienda que una solicitud de servicio es una solicitud formal que un usuario final o cliente envía a la mesa de servicio de TI para iniciar una acción de servicio de TI. Por lo tanto, la gestión de solicitudes de servicio es una función principal de las unidades o áreas de tecnologías de cualquier compañía. 
      .col-lg-10
        .BG05.p-4.mb-4
          .bloque-texto-c
            i.fas.fa-quote-right(style="font-size: 1.8em")
            h4.mb-2 La biblioteca de infraestructura de tecnologías de información (ITIL, por sus siglas en inglés) la define como "una práctica para soportar la calidad de los servicios acordados al manejar las solicitudes iniciadas por el usuario de una manera eficiente e intuitiva".
            span -  Citado en ManageEngine, 2020.
        p Dentro de los tipos de solicitud de servicio se puede encontrar:
        
        ul.lista-ul--color.mb-4
          li
            <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
            | Solicitud de información como los límites de almacenamiento en la nube.
          li
            <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
            | Solicitud de acceso a un documento, servicio, plataforma o red.
          li
            <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
            p.mb-0 Solicitud de un recurso, en los casos cuando se necesitan periféricos #[em hardware] como una PC, #[em laptop], teclado o también puede ser #[em software].
        
        .BG04.p-4.mb-4
          .bloque-texto-c
            i.fas.fa-quote-right(style="font-size: 1.8em")
            h4.mb-2 Las solicitudes de servicio deben cumplirse en función de flujos de trabajo ya definidos, que pueden variar su complejidad, por lo que es importante que dichos flujos de trabajo deben estandarizarse y probarse para prestar los servicios dentro de los niveles de servicio acordados o SLA.
            span - ManageEngine, 2020

    p A continuación se presenta un ejemplo del flujo de trabajo de la gestión de solicitudes de servicio.  

    .row.justify-content-center.mb-4(data-aos="zoom-in")
      .col-lg-10.mb-4
        .titulo-sexto.color-acento-contenido
          h5 Figura 3
          span Ejemplo de flujo de trabajo de gestión de solicitudes
      .col-lg-10.d-none.d-lg-flex
        figure
          img(src="@/assets/curso/tema4/img03.svg")
          figcaption Nota. Tomado de ManageEngine (2020).
      .col.d-lg-none.d-flex
        figure
          img(src="@/assets/curso/tema4/img04.svg")
          figcaption Nota. Tomado de ManageEngine (2020).

    .BGR09.px-md-5.px-4
      p Es muy importante que se relacione este flujo de trabajo con la gestión de las solicitudes y el rol que toma el catálogo de servicios frente a cada fase, según lo indica ManageEngine (2020): 
      
      .titulo-sexto.color-acento-contenido.mb-4
        h5 Cuadro comparativo entre el flujo de solicitudes y el rol del catálogo de servicios
    
      .row.justify-content-center.mb-4(data-aos="zoom-in")
        .col-lg-10
          SlyderF.mb-5(columnas="col-12")
            .row.justify-content-center
              img(src="@/assets/curso/tema4/img05.svg")
            .row.justify-content-center
              img(src="@/assets/curso/tema4/img06.svg")
            .row.justify-content-center
              img(src="@/assets/curso/tema4/img07.svg")
            .row.justify-content-center
              img(src="@/assets/curso/tema4/img08.svg")

    .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4
        img(src='@/assets/curso/temas/img01.svg' style="max-width: 32px;" data-aos="fade-right")
        h3.col.ps-3.mb-0.text-primario(data-aos="fade-left") Catálogo de servicios
    
    p Un catálogo de servicios de TI se presenta como una fuente de información confiable sobre todos los servicios de TI que ofrece la unidad de tecnologías de una organización.

    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-lg-10.mb-4
        .BG04.p-4
          .bloque-texto-c
            i.fas.fa-quote-right(style="font-size: 1.8em")
            h4.mb-2 ITIL define un catálogo de servicios como una base de datos centralizada que contiene información acertada sobre las ofertas de servicios de TI activas, es decir, es un mostrador o vitrina desde el cual los usuarios finales (internos o externos) solicitan servicios y productos desde la mesa de servicios de TI.
      .col-lg-4.col-8.mb-lg-0.mb-4
        img(src="@/assets/curso/tema4/img09.png")
      .col-lg-8
        p Entonces, ¿cuáles son los #[b componentes de un catálogo de servicios y sus beneficios]?
        p El catálogo de servicios proporciona claridad a los usuarios finales sobre los servicios ofrecidos y generalmente incluye la siguiente información:
        ul.lista-ul--color
          li
            <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
            | Categoría del servicio.
          li
            <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
            | Descripción del servicio.
          li
            <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
            | Disponibilidad del servicio,
          li
            <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
            | SLA específicos del servicio.
          li
            <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
            | Propietario del servicio.
          li
            <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
            | Costos del servicio (si procede).

    p En esencia, el catálogo de servicios es parecido a un menú de un restaurante o una lista de productos en un sitio web de comercio electrónico. Sin esto, los clientes no podrían hacer un pedido, por lo tanto, su objetivo es generar beneficios para los usuarios finales y las organizaciones. Entre los más representativos se tienen los siguientes:

    .tarjeta--container.row
      .col-md.BGR03C.p-5(data-aos="fade-right")
        .row.justify-content-center.mb-4
          .col-4
            img(src='@/assets/curso/tema4/img10.svg')
        .h4 Agiliza la comunicación
        p.mb-0 Un catálogo de servicios diseñado acertadamente actúa como el único punto de contacto, para que los usuarios finales vean la lista de servicios disponibles y sus características.
      .col-md.BG04.p-5(data-aos="fade-right")
        .row.justify-content-center.mb-4
          .col-4
            img(src='@/assets/curso/tema4/img11.svg')
        .h4 Estandariza la prestación de servicios
        p.mb-0 Al entregar una lista de servicios selecta y definir los parámetros de entrega asociados.
      .col-md.BGR05A.p-5(data-aos="fade-right")
        .row.justify-content-center.mb-4
          .col-4
            img(src='@/assets/curso/tema4/img12.svg')
        .h4 Optimiza los costos
        p.mb-0 Se tiene el control de la oferta de servicios, su demanda y uso, por lo que las compañías pueden utilizar el catálogo de servicios como una herramienta para identificar las ofertas de alto valor que son críticas para el negocio.

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
