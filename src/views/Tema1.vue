<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Técnicas de recolección de la información

    p En el campo investigativo la información toma un papel protagónico, por su condición tanto de materia prima de análisis como de resultado final. Y es que el estudio de cualquier tipo de situación o hecho busca aprender de sí mismo, bien sea para prevenir su ocurrencia, aprovecharla o anticiparla. 
    p.mb-5 Con el objetivo de adentrarse en las diferentes metodologías de recolección de información, primero hace falta definirla y distanciarla de otros términos con los cuales puede ser confundida o reemplazada. Aunque estos aspectos pueden parecer muy elementales, marcan una diferencia a la hora de iniciar una investigación de cualquier naturaleza.

    .BGM01.px-md-5.px-4
      .row.justify-content-center.mb-4
        .col-lg-10.mb-4
          .bloque-texto-a.color-primario.p-4.p-md-5.mb-5 
            .row.m-0.align-items-center.justify-content-between
              .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
                h4.mb-2 Entonces, ¿cómo se puede definir la información en la jerga investigativa?
                .row.justify-content-center
                  .col-8
                    img(src="@/assets/curso/tema1/img01.svg")
              .col-lg-8(data-aos="fade-left")
                .bloque-texto-a__texto.p-4
                  p La <span style="color=#3185AF">#[b información]</span> es el resultado de la disposición de otro contenido, de tal forma que se le dote de una utilidad o propósito específico. Así, la forma previa de la información son <span style="color=#3185AF">los datos</span>, que pueden definirse como una serie de registros o caracteres alfanuméricos que carecen de sentido.
                  .h5.text-primario.mb-0 Cuando se otorga un contexto a los datos se transforman en información y se revisten de una función.
        .col-lg-10
          p Para comprender mejor estos conceptos vea el siguiente ejemplo:
          p La información se puede presentar de multitud de formas, obedeciendo a distintos criterios que toman mayor importancia según la disciplina en la que sean utilizados. En el campo empresarial algunas de las clasificaciones más utilizadas son:
          .row.justify-content-center.align-items-center.BG02.mb-4(data-aos="flip-up")
            .col-lg-8.order-lg-1.order-2.p-4
              p.mb-0 Si tengo una lista de valores que no obedece a una escala ni presenta un orden determinado carece de significado; pero si conozco que esta lista corresponde a las unidades vendidas de cada uno de los productos que ofrece la empresa, trascienden de datos a información histórica o presente del volumen de ventas de una organización. Es así como obtienen relevancia y utilidad, pues permitirán medir la gestión comercial, el posicionamiento de la empresa o la evolución respecto a periodos anteriores.
            .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
              img(src="@/assets/curso/tema1/img02.svg")

    .row.justify-content-center.mb-4(data-aos="zoom-in")
      AcordionA.mb-5(tipo="a" clase-tarjeta="BGIMG01")
        .row.justify-content-center(titulo="Según su naturaleza")
          .col-lg-4.col-10.mb-lg-0.mb-4
            figure.mb-4
              img(src="@/assets/curso/tema1/img03.png")
            .h4.text-primario Cualitativa
            p.mb-0 Corresponde a datos de tipo descriptivo, centrados en la presentación de características que permiten entender una situación o elemento. En una empresa, este tipo de información tiene especial relevancia cuando se trata de presentar un proceso determinado, la descripción de una estrategia aplicada o el recuento de una situación problemática o susceptible de mejora, entre otros.
          .col-lg-4.col-10.mb-lg-0.mb-4
            figure.mb-4
              img(src="@/assets/curso/tema1/img04.png")
            .h4.text-primario Cuantitativa
            p Este tipo de información se caracteriza por presentarse en cantidades, es decir, los datos son numéricos y obedecen a algún tipo de escala. Así, normalmente se hace uso de esta información para presentar datos de recaudo, ventas o apalancamiento. Goza de mayor objetividad, puesto que la escala no suele depender del investigador, ni del interprete. 
            p Por ejemplo, los días que pasan entre la venta de un producto y el recaudo del dinero, pueden contrastarse con los que da un proveedor después de entregar la materia prima, definir cuál ocupa un periodo de tiempo más largo no es susceptible a distintas opiniones.
            .row.justify-content-center
              .col-auto
                a.boton.color-acento-botones.indicador__container(@click="modal1 = true")
                  span Para tener en cuenta…
                  i.fas.fa-chevron-circle-up
                  .indicador--click(v-if="mostrarIndicador")
          .col-lg-4.col-10.mb-lg-0.mb-4
            figure.mb-4
              img(src="@/assets/curso/tema1/img05.png")
            .h4.text-primario Cualitativa - Cuantitativa
            p Es posible que ambos tipos de información se complementen y permitan entregar resultados mucho más completos a los interesados. Claro ejemplo de ello son los estados financieros, que ofrecen diversos valores que dan cuenta de la estructura financiera y el resultado del ejercicio de una compañía; pero que por disposición normativa deben venir acompañados de unas revelaciones, cuyo detalle suele incluir una descripción detallada de las características de cada rubro.
        .row.justify-content-center(titulo="Según su destinatario")
          .col-lg-6.col-10.mb-lg-0.mb-4
            figure.mb-4
              img(src="@/assets/curso/tema1/img07.png")
            .h4.text-primario Interna
            p.mb-0 Es la información recolectada para el interior de la organización. Usualmente involucra un número limitado de personas, sobre las cuales se aplican los instrumentos elegidos para ello.  Puede comprender temáticas restringidas, como las recetas aplicadas en la producción para darle al producto un sabor característico, hasta aspectos mucho más universales, como la edad promedio de la planta de personal.
          .col-lg-6.col-10.mb-lg-0.mb-4
            figure.mb-4
              img(src="@/assets/curso/tema1/img08.png")
            .h4.text-primario Externa
            p.mb-0 Recolecta los datos y los presenta de tal forma que le puedan ser de utilidad a un gran número de personas. Un ejemplo de ello, es la rendición de cuentas que ofrecen las compañías que administran recursos de terceros. Se diseñan informes en los que se da claridad respecto a cada proceso a quienes hayan invertido o deseen invertir en la empresa, por lo que gozan de plena libertad para ser interpretada o compartida.
        .row.justify-content-center(titulo="Según su restricción")
          .col-lg-4.col-10.mb-lg-0.mb-4
            figure.mb-4
              img(src="@/assets/curso/tema1/img09.png")
            .h4.text-primario Privilegiada
            p.mb-0 Es la información con mayor cantidad de barreras y dirigida a un número muy limitado de personas. Un claro ejemplo de ello son los códigos fuentes de #[em software] licenciado o las contraseñas de acceso a las cuentas bancarias. Su publicación o fuga puede llegar a tener un fuerte impacto sobre los intereses de la empresa y sus administradores.
          .col-lg-4.col-10.mb-lg-0.mb-4
            figure.mb-4
              img(src="@/assets/curso/tema1/img10.png")
            .h4.text-primario Privada
            p.mb-0 Se ubica en un rango intermedio, por lo que existen restricciones respecto a su uso; pero los usuarios interesados son muchos más. En esta categoría podrían incluirse aspectos como el número telefónico de personas expuestas públicamente, historiales crediticios o grabaciones de reuniones con el personal de nivel táctico u operativo.
          .col-lg-4.col-10.mb-lg-0.mb-4
            figure.mb-4
              img(src="@/assets/curso/tema1/img11.png")
            .h4.text-primario Pública
            p.mb-0 En esta categoría se maneja información sin restricción de acceso, es decir, cualquier tipo de reporte, declaración o informe que pueda ser conocido por cualquier persona. A diferencia de los casos anteriores, aquí puede resultar beneficioso que la información se masifique, por ejemplo, si se habla de una campaña publicitaria para un producto, el posicionamiento de una empresa como líder del mercado o el reconocimiento de algún premio por la aplicación de políticas amigables con el medio ambiente.

    ModalA(:abrir-modal.sync="modal1")
      .row.align-items-center
        .col-lg-3.col-6.mb-lg-0.mb-4
          img(src="@/assets/curso/tema1/img06.png")
        .col-lg-8
          h4.text-white Para tener en cuenta…
          p.text-white Este sistema suele ser el más utilizado para clasificar la información en ambientes administrativos, ya que con ello es posible elegir una metodología que se ajuste al tipo de datos que serán suministrados por las personas involucradas. Para la recolección de información, la naturaleza cuantitativa ofrece mayores facilidades si se busca abordar un gran número de personas, puesto que existen estrategias para consolidar la información en un número reducido de variables. 

    p La correcta clasificación de la información puede redundar en políticas de recolección y análisis más apropiadas para el propósito de los investigadores, es por ello que comprender cada categoría puede permitir una mejor planeación a la hora de ejecutar estrategias relacionadas con su recolección.
    p Teniendo claridad sobre qué es la información, su naturaleza y su importancia en la gestión administrativa es procedente dar cabida a las técnicas para su recolección. 

    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-lg-10.BG03
        .row.justify-content-center
          .col-lg-1.col-2.px-0.order-1
            img(src="@/assets/curso/tema1/img12.svg")
          .col-lg-7.order-lg-2.order-3
            .p-4
              p.mb-0 Las técnicas surgen como herramientas procedimentales y prácticas a través de las cuales se obtendrán los datos necesarios para llevar a cabo el trabajo de análisis, por lo que los resultados a conseguir dependerán en gran medida del acierto en la elección de las metodologías apropiadas.
          .col-lg-4.col-8.px-0.order-lg-3.order-2.mb-lg-0.mb-4
            figure.mt-lg-4
              img(src="@/assets/curso/tema1/img13.svg")
          
    separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Criterios de selección
    
    p.mb-5 La información puede ser tomada del ambiente a partir de diferentes modelos; sin embargo, existen una serie de elementos que condicionan su naturaleza, y por lo tanto, responden mejor a ciertos procedimientos. A continuación, se presentan los aspectos a tener en cuenta a la hora de elegir el sistema más adecuado para la recolección de la información:

    .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4
        img(src='@/assets/curso/temas/img01.svg' style="max-width: 32px;" data-aos="fade-right")
        h3.col.ps-3.mb-0.text-primario(data-aos="fade-left") Definir el tipo de información a recolectar

    p Según el propósito y el área que se desee auditar o evaluar en una organización, el tipo de contenido con el que se puede encontrar el encargado del trabajo puede variar, por ejemplo, vea qué podría pasar en la evaluación de gestión del área financiera:

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta--container.row
          .col-md.BGR04A.p-5(data-aos="fade-right")
            .row.justify-content-center.mb-4
              .col-6
                img(src='@/assets/curso/tema1/img14.svg')
            p.mb-0 Puede predominar el estudio de indicadores, la evaluación de resultados, la composición de la estructura financiera, entre otros. Así, es probable que la mayor cantidad de información obtenida y relevante pueda ser expresada en valores y, por lo tanto, ser susceptible de herramientas de análisis como la tabulación o los gráficos que aporten contenido relevante al resultado.
          .col-md.BGR05A.p-5(data-aos="fade-left")
            .row.justify-content-center.mb-4
              .col-6
                img(src='@/assets/curso/tema1/img15.svg')
            p.mb-0 Por otra parte, si lo que se espera diagnosticar, es la aplicación de políticas de servicio al cliente, es probable que el análisis apunte a la revisión de testimonios, a las estrategias para abordar a quien presenta quejas o reclamos o la actitud de los asesores. En este sentido, prima información de aspecto cualitativo, por lo que el análisis y sus conclusiones pueden apegarse más al ámbito descriptivo, presentando reseñas sobre los elementos clave del trabajo efectuado por el personal de área evaluada.

    .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4
        img(src='@/assets/curso/temas/img01.svg' style="max-width: 32px;" data-aos="fade-right")
        h3.col.ps-3.mb-0.text-primario(data-aos="fade-left") Estimar la cantidad de personas o elementos a indagar
    
    p Si la evaluación se focaliza en un número reducido de personas o actividades el auditor puede efectuar un trabajo más individualizado, tratando con cada persona de forma directa y destinando todo el tiempo que considere necesario para obtener la mayor cantidad de información posible. Vea el siguiente ejemplo:
      
    .row.justify-content-center.mb-4
      .col-lg-6.mb-lg-0.mb-4(data-aos="fade-right")
        p.mb-0 Si se espera analizar la idoneidad de los procesos productivos de una planta con cinco trabajadores, a cada uno de ellos se les podrá hacer todas las preguntas y retroalimentaciones que surjan durante el acercamiento, lo que permite ahondar en problemáticas no contempladas inicialmente o encauzar el trabajo a aspectos específicos que se determinen en el proceso.
      .col-lg-6(data-aos="fade-left")
        p.mb-0 En cambio, si el aspecto estudiado involucra muchos individuos, es posible que deba limitarse el tiempo que se destine a cada uno de ellos; en algunos casos puede ser necesario estandarizar la recolección de información para aplicar a grandes grupos de forma más rápida. En estos casos, la calidad de la información y su nivel de detalle suelen disminuir, pero permiten obtener una visión general cercana a la realidad.

    .row.justify-content-center.mb-4
      .col-lg-10
        figure.mb-4(data-aos="zoom-in")
          img(src='@/assets/curso/tema1/img16.png')
        .h5.text-primario.text-center(data-aos="fade-right") Entonces, ¿cuál puede ser una situación práctica que se genere frecuentemente en estas condiciones?
        .hr-primario

    p Una situación práctica que se genera con frecuencia es la recolección de información respecto a la calidad o efectividad de un producto o servicio vendido a los clientes de la organización. Un formulario que contenga preguntas concretas y rápidas de responder puede resultar una buena forma de realizar el primer acercamiento a la percepción general de la demanda respecto a una referencia en particular.

    .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4
        img(src='@/assets/curso/temas/img01.svg' style="max-width: 32px;" data-aos="fade-right")
        h3.col.ps-3.mb-0.text-primario(data-aos="fade-left") Evaluar las regulaciones aplicables
    
    p Si el objetivo detrás del estudio es la implementación de estrategias en un proceso interno de mejora, las exigencias serán determinadas por la misma organización, lo que ofrece flexibilidad a la hora de elegir metodologías de recolección y análisis de los datos. 

    .BG04.mb-4(data-aos="flip-up")
      .row.justify-content-center
        .col-lg-4.col-8.py-4
          img(src='@/assets/curso/tema1/img17.svg')
        .col-lg-8.p-4
          p De esta forma, el trabajo obedecerá a unos propósitos de gestión que pueden refinarse en la ejecución del trabajo. Así, el auditor o investigador puede tomar libertades creativas en la aplicación de medidas que apunten a la obtención de información veraz, diseñando papeles de trabajo a la medida.
          p.mb-0 Si se trata de un trabajo enfocado a la certificación en algún estándar en particular el trabajo será mucho más regulado, lo que implica mantenerse dentro de un margen más restrictivo en cuanto a los sistemas aplicados para llevar a cabo la tarea. 

    p Para este tipo de situaciones el trabajo del analista debe someterse a las indicaciones descritas por la autoridad competente, por lo que la elección de las metodologías de recolección probablemente no dependa de él.
    .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4
        img(src='@/assets/curso/temas/img01.svg' style="max-width: 32px;" data-aos="fade-right")
        h3.col.ps-3.mb-0.text-primario(data-aos="fade-left") Contemplar los recursos disponibles
    
    p Los trabajos asociados con el estudio y análisis de la información pueden ser tan variados como la creatividad de los investigadores que los ejecutan.

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-10.mb-4
        .bloque-texto-g.color-primario.bloque-inv.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/img18.svg')})`}"
          )(data-aos="fade-left")
          .bloque-texto-g__texto.p-4(data-aos="fade-right")
            p.mb-0 En el ámbito empresarial existe un principio administrativo conocido como 
            .h5.text-primario costo-beneficio, 
            p.mb-0 y como su nombre lo indica, cualquier medida implementada debe propender por la obtención de beneficios, que en conjunto, superen el esfuerzo y los costos asociados con ella.
      .col-lg-10
        p En términos prácticos, toda estrategia debe justificar su ejecución al aportar a la empresa más de lo que le cuesta. En este aspecto si una empresa busca implementar controles de calidad, estos deben reducir las pérdidas ocasionadas por productos defectuosos a los que se les solicita la garantía a un nivel en el que le ahorren a la empresa más gastos que los que demandó llevar a cabo la aplicación de los controles.
        .BG06(data-aos="flip-up")
          .row.justify-content-center.align-items-end
            .col-lg-4.col-6
              img(src='@/assets/curso/tema1/img19.png')
            .col-lg-8.p-4
              .row.mb-4
                .col-auto.BG02.p-2
                  .h5.text-primario.mb-0 Es muy importante que tenga en cuenta que
              p.text-white Si las metodologías de recolección de información son muy complejas o requieren mucho tiempo y personal, su costo se irá incrementando de forma proporcional. Es por ello que durante la fase de planeación es necesario contar con un presupuesto detallado que contemple los recursos que serán necesarios. A partir de ello, se podrán programar medidas más o menos costosas. 
              p.text-white.mb-0 Así, si se busca realizar acercamientos a trabajadores en las distintas sedes de una compañía que opera a nivel nacional, pueden evaluarse alternativas como videollamadas o comunicación diferida, que reduzcan los costos de desplazamiento, así como el tiempo que este tipo de labores involucra.

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Observación
    
    p.mb-5 La observación es la acción que desarrolla cualquier persona (o incluso animal) para obtener información del entorno que lo rodea. Es gracias a ella que se registran situaciones, eventos o lugares en un tiempo determinado, y que se asocian a estímulos o acciones, por ejemplo, cuando se pasa frente a una calle llena de restaurantes es normal analizar su oferta gastronómica para luego priorizarlas en función de los gustos personales. Conozca los beneficios de esta técnica:

    .row.justify-content-center.mb-5(data-aos="zoom-in")
      .col-lg-10.mb-4
        .titulo-sexto.color-acento-contenido.mb-4
          h5.mb-0 Beneficios de la técnica de la observación
      .col-lg-10.d-none.d-lg-flex
        img(src="@/assets/curso/tema1/img20.svg")
      .col-12.d-lg-none.d-flex
        img(src="@/assets/curso/tema1/img21.svg")
    
    p Para aplicar la metodología de forma apropiada es recomendable efectuar una serie de acciones que apunten a obtener información en la cantidad y calidad suficiente para satisfacer los requerimientos asociados con el trabajo:

    .row.justify-content-center.mb-4
      .col-xl-3.col-md-6.col-10.mb-xl-0.mb-4(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img22.svg' alt='AvatarTop')
          .BG04B.p-4
            h4.text-center.mt-5 Determinar el objeto de la observación
            p.mb-0 Esto significa tener claridad de qué es lo que se va a observar y para qué se hará; se encuentra estrechamente asociado con el objetivo del estudio, tener claridad de su propósito permite enfocar el trabajo en una dirección u otra.
      .col-xl-3.col-md-6.col-10.mb-xl-0.mb-4(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img23.svg' alt='AvatarTop')
          .BG03B.p-4
            h4.text-center.mt-5 Secuencia de acciones
            p.mb-0 Planear una secuencia de acciones determinada, que permita seguir un cronograma de actividades de forma eficiente y aprovechando los recursos disponibles.
      .col-xl-3.col-md-6.col-10.mb-xl-0.mb-4(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img24.svg' alt='AvatarTop')
          .BG04B.p-4
            h4.text-center.mt-5 Cumplir con las proyecciones
            p.mb-0 Ejecutar el trabajo tratando de cumplir con las proyecciones, esto maximizará la efectividad del trabajo de observación, por ejemplo, si se busca medir la capacidad de los empleados en situaciones determinadas, se debe acudir en el momento en el que las condiciones sean idóneas para evidenciar de forma clara la situación.
      .col-xl-3.col-md-6.col-10(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img25.svg' alt='AvatarTop')
          .BG03B.p-4
            h4.text-center.mt-5 Equipo de trabajo competente
            p.mb-0 Si el trabajo lo amerita, designar un equipo de trabajo competente y que se complemente en las labores, de tal forma que su trabajo mancomunado potencie los resultados. Es recomendable que el observador sea un experto en la materia estudiada, puesto que su criterio puede aportar al análisis desde las etapas tempranas de la ejecución.

    p.mb-5 La aplicación de esta metodología puede ser tan estructurada como la situación evaluada lo amerite, es por ello que se han diseñado instrumentos que funcionan como herramientas que apoyan la labor y le permiten ejecutar el trabajo de una forma organizada y controlada. Emanuelli (2012) presenta algunos de ellos:

    .row.justify-content-center.mb-4(data-aos="zoom-in")
      TabsC.color-acento-botones
        .py-4.py-md-5(titulo="<b>El diario</b>")
          .row.justify-content-center
            .col-lg-7.order-lg-1.order-2.p-4
              p Funciona como un cuaderno, en el cual se registran todas las situaciones asociadas a la observación. Es muy flexible en cuanto a estructura y diligenciamiento, por lo que puede incluir observaciones, consejos o comentarios. Incluso imágenes, dibujos o gráficos que aporten al análisis. Actualmente es posible contar con ellos a través de celulares o computadores, haciendo uso de herramientas como un bloc de notas o procesadores de texto. 
              p.mb-0  Se recomienda que las aportaciones escritas sean lo suficientemente claras para ser consultadas a futuro, lo que implica un nivel de detalle suficiente para no dejar espacio a interpretaciones. Para que esto sea posible es necesario diligenciarlo de forma continua, durante la ejecución de las tareas de observación, puesto que así se garantiza el mayor nivel de fidelidad. 
            .col-lg-3.col-6.order-lg-2.order-1.mb-lg-0.mb-4
              img(src="@/assets/curso/tema1/img26.png")
        .py-4.py-md-5(titulo="<b>Mapas</b>")
          .row.justify-content-center
            .col-lg-7.order-lg-1.order-2.p-4
              p En esta categoría se incluyen diagramas, planos y cualquier tipo de figura que aporte información complementaria al diario. Tienen especial utilidad para trabajos que involucran distintas locaciones, por ejemplo, si se están evaluando las rutas de distribución de los productos, es posible resaltar las vías utilizadas sobre un mapa de cada ciudad o municipio, y con ello identificar rutas más cortas o seguras.
              p.mb-0 Al igual que en el caso anterior, entre más información se registre, mayor claridad habrá a la hora de alcanzar conclusiones. Complementando el ejemplo previo, pueden colorearse las zonas en función de los niveles de tráfico o de acuerdo con las estadísticas de delincuencia publicadas por las autoridades, y con ello sustentar cualquier tipo de decisión. 
            .col-lg-3.col-6.order-lg-2.order-1.mb-lg-0.mb-4
              img(src="@/assets/curso/tema1/img27.png")
        .py-4.py-md-5(titulo="<b>Dispositivos mecánicos</b>")
          .row.justify-content-center
            .col-lg-7.order-lg-1.order-2.p-4
              p Pertenecen a esta categoría todas las herramientas que permiten registrar las situaciones de forma directa de la fuente. En este sentido, si se está consultando a los clientes por su nivel de satisfacción con el producto, hacer uso de sistemas de grabación permite la consulta posterior de las respuestas, es por ello que muchas entidades informan que las llamadas serán grabadas para efectos de calidad y evaluación. 
              p.mb-0 En este rubro también se incluyen sistemas como las cámaras fotográficas o de video, que permiten conservar aún más información en otros formatos, lo que dota de facilidades el trabajo del auditor, sobre todo cuando quiere retomar eventos pasados.
            .col-lg-3.col-6.order-lg-2.order-1.mb-lg-0.mb-4
              img(src="@/assets/curso/tema1/img28.png")
        .py-4.py-md-5(titulo="<b>Cuadros de trabajo</b>")
          .row.justify-content-center
            .col-lg-7.order-lg-1.order-2.p-4
              p Complementan el trabajo de registro previo y consiste en la generación de tablas que compilen la información recolectada. Según la cantidad de información puede variar su distribución; pero, la forma más utilizada consiste en disponer a los participantes en las filas y las respuestas en las columnas. 
              p.mb-0 Esta herramienta aporta mucha utilidad cuando la información es diversa y proviene de distintas fuentes, puesto que al consolidar los datos permite presentarlos de una forma más amigable para los interesados. Cabe resaltar que este sistema tiene aplicabilidad prácticamente en todas las metodologías de recolección de la información.
            .col-lg-3.col-6.order-lg-2.order-1.mb-lg-0.mb-4
              img(src="@/assets/curso/tema1/img29.png")
    
    p.mb-5 A continuación se presenta un ejemplo en el que un concesionario quiere identificar los colores más demandados para cada uno de sus modelos de vehículos, por lo que se anotaron el modelo y el color de todos los carros que ingresaron a revisión periódica en una semana, así:  

    .row.justify-content-center.mb-4
      .col-lg-10
        .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
          h5 Tabla 1
          span Formato cuadro de trabajo

        .tabla-a.color-acento-botones.mb-5(data-aos="zoom-in")
          table
            thead(style="border-color: #DAE27F")
              tr
                th(style="background-color: #DAE27F;").text-center Color
                th(style="background-color: #DAE27F;").text-center Modelo 1
                th(style="background-color: #DAE27F;").text-center Modelo 2
                th(style="background-color: #DAE27F;").text-center Modelo 3
                th(style="background-color: #DAE27F;").text-center Total
            tbody
              tr
                td(style="background-color: #E8F2F6;").text-center.text-bold Blanco
                td(style="background-color: #E8F2F6;").text-center 8
                td(style="background-color: #E8F2F6;").text-center 9
                td(style="background-color: #E8F2F6;").text-center 9
                td(style="background-color: #E8F2F6;").text-center 26
              tr
                td.text-center.text-bold Negro
                td.text-center 10
                td.text-center 7
                td.text-center 8
                td.text-center 25
              tr
                td(style="background-color: #E8F2F6;").text-center.text-bold Rojo
                td(style="background-color: #E8F2F6;").text-center 6
                td(style="background-color: #E8F2F6;").text-center 8
                td(style="background-color: #E8F2F6;").text-center 9
                td(style="background-color: #E8F2F6;").text-center 23
              tr
                td.text-center.text-bold Gris
                td.text-center 5
                td.text-center 6
                td.text-center 7
                td.text-center 18
              tr
                td(style="background-color: #E8F2F6;").text-center.text-bold Total
                td(style="background-color: #E8F2F6;").text-center 29
                td(style="background-color: #E8F2F6;").text-center 30
                td(style="background-color: #E8F2F6;").text-center 33
                td(style="background-color: #E8F2F6;").text-center 92

    p La elaboración del cuadro anterior permite analizar la información desde una nueva perspectiva y alcanzar nuevas conclusiones, por ejemplo, que el modelo 3 tiene mayor aceptación a nivel comercial, que el color más común es el blanco o que la combinación más popular es el modelo 1 de color negro, entre otros.

    separador
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Entrevista
    
    p Se considera una de las metodologías más útiles para recolectar información cualitativa, dado que facilita las interacciones entre las partes. El entrevistador suele contar con una batería de preguntas dirigidas a obtener datos relevantes de los sujetos entrevistados y encontrar elementos comunes entre cada uno de ellos, para identificar patrones o situaciones que demanden atención.

    .BG06.mb-4(data-aos="flip-up")
      .row.justify-content-center.align-items-center
        .col-lg-3.col-6
          img(src='@/assets/curso/tema1/img30.png')
        .col-lg-8
          .p-4
            .h5.text-white.mb-5 De acuerdo con esto, ¿cuál es la diferencia más significativa entre la entrevista y la observación?
            .tabla-a.color-primario
              table
                thead(style="border-color: #fff; border: 2px solid #fff")
                  tr
                    th(style="background-color: #fff;").text-center.text-primario Observación
                    th(style="background-color: #fff;").text-center.text-primario Entrevista
                tbody
                  tr
                    td(style="border: 2px solid #fff").text-white El investigador tiene la posibilidad de interactuar con los sujetos evaluados, lo que significa que es posible encauzar el instrumento a una posición en la que suministre la información que se requiere.
                    td(style="border: 2px solid #fff").text-white El investigador se aísla de los eventos estudiados, limitando su margen de maniobra para encontrar las situaciones esperadas.
        .col-lg-1.d-none.d-lg-flex

    p.mb-5 Como ya se mencionó, la metodología de la entrevista se centra en la interacción con los sujetos investigados a través de un diálogo, según el tipo de conversación permite clasificar la entrevista entre las siguientes posibilidades:

    .row.justify-content-center.mb-4(data-aos="zoom-in")
      .col-lg-10.mb-4
        .titulo-sexto.color-acento-contenido
          h5 Figura 1
          span Tipos de entrevista
      .col-lg-10.d-none.d-lg-flex
        img(src="@/assets/curso/tema1/img31.svg")
      .col.d-lg-none.d-flex
        img(src="@/assets/curso/tema1/img32.svg")

    p La entrevista puede ser muy efectiva para obtener información de parte de los empleados o terceros involucrados con los procesos en evaluación, del acercamiento con ellos pueden surgir apreciaciones que los evaluadores han pasado por alto como, por ejemplo, la forma en la que reaccionan los clientes a las características específicas de un producto, su precio o su presentación. 

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-10.mb-4
        .bloque-texto-g.color-primario.bloque-inv.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/img33.jpg')})`}"
          )(data-aos="fade-left")
          .bloque-texto-g__texto.p-4(data-aos="fade-right")
            p.mb-0 La comunicación asertiva aporta un ambiente organizacional más ameno, en algunas ocasiones los empleados perciben desinterés por parte de sus superiores, por lo que definir entrevistas periódicamente para escuchar sus opiniones puede tener implicaciones emocionales que redunden en la productividad y en la generación de un sentido de pertenencia.
    
    p Para llevar a cabo una entrevista efectiva es recomendable que se tomen en cuenta ciertas prácticas que garanticen una adecuada ejecución para la obtención de los resultados esperados. Las siguientes son algunas de las actividades a tener presente para el buen uso de esta metodología: 

    .BGM01.px-md-5.px-4.mb-5(data-aos="zoom-in")
      PasosA.color-acento-contenido(tipo="n")
        .row.justify-content-center(data-aos="fade-right")
          .h4 Definición de la problemática
          p.mb-0 Como en cualquier sistema de recolección de información es importante dirigir todos los esfuerzos a la consecución de datos relevantes para la problemática que se está abordando. Sin una debida justificación la entrevista carecerá de sentido y dificultará tanto el trabajo del entrevistador como las posibles respuestas del entrevistado. Si es posible, además de presentar la problemática de forma precisa, debe estimarse el horizonte de tiempo en el que se espera solucionar.
        .row.justify-content-center(data-aos="fade-left")
          .h4.text-end Estimar el tamaño de la muestra
          p.mb-0 Definir las personas a las que se les hará la aproximación puede resultar útil para la estimación del presupuesto y el margen de error esperado. Entre más personas sean abordadas, más posibilidades habrá de alcanzar conclusiones cercanas a la realidad, de la misma forma, si se determina restringir el estudio a zonas geográficas, la planificación para aspectos como transporte y disponibilidad de los entrevistadores puede facilitar el contar con los recursos necesarios para llevar a cabo el trabajo.
        .row.justify-content-center(data-aos="fade-right")
          .h4 Planificación de la entrevista
          p Para el ámbito administrativo no se acostumbra realizar entrevistas improvisadas porque se rompe con el esquema de planificación y desarrollo de la problemática que motivó el trabajo de investigación. La entrevista puede dividirse en tres momentos fundamentales: comienzo, desarrollo y cierre.
          .BGR07.p-3.mb-5
            .row.justify-content-around.align-items-center
              .col-3.col-sm-2.col-lg-1
                img(src="@/assets/curso/temas/img02.svg")
              .col
                .row.justify-content-between.align-items-center
                  .col.mb-3.mb-sm-0
                    p.text-white.mb-0 Para conocer qué se realiza en cada uno de estos momentos consulte el siguiente PDF.
                  .col-sm-auto
                    a.boton.color-acento-botones(:href="obtenerLink('downloads/partes_de_la_entrevista.pdf')" target="_blank")
                      span Descargar
                      i.fas.fa-file-download
        .row.justify-content-center(data-aos="fade-left")
          .h4.text-end Análisis de la información
          p Una vez finalice el acercamiento con los sujetos estudiados es necesario iniciar un proceso de lectura y análisis de las respuestas obtenidas. Debido a su naturaleza, la información estará dispersa entre sus argumentos y será necesario evaluar con ojo crítico la verdadera posición del entrevistado. Dispositivos como las cámaras o grabadoras de audio pueden resultar de especial utilidad, puesto que el registro escrito puede dejar de lado aspectos relevantes como el lenguaje corporal o la intencionalidad a la hora de dar las respuestas. 
          p.mb-0 Inevitablemente, el análisis de las respuestas tendrá un alto componente subjetivo, ya que pueden darse distintas interpretaciones a partir de un mismo enunciado. Para minimizar este potencial riesgo de sesgo se recomienda que se involucren otros expertos y buscar aquellos elementos comunes obtenidos tras su análisis. 

    separador
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.4 Encuesta
    
    p Este sistema consiste en el registro de situaciones, a partir de cuya información se procede a indagar a las personas que la suministraron. Este es un método descriptivo, centrado en identificar y distinguir hábitos, ideas, preferencias, entre otros.

    .cajon.color-secundario.p-4.mb-4(data-aos="flip-up")
      .row.justify-content-between.align-items-center
        .col-lg-10.order-lg-1.order-2
          p.mb-0 Al igual que con las entrevistas, existen limitaciones económicas, de tiempo y de personal que impiden que se pueda recolectar la información de todos los individuos de una población que se espera estudiar.  Es por ello que se hace necesario la selección aleatoria o discrecional de personas a encuestar, cuyos resultados y conclusiones sean extrapolados a la totalidad de la población. Este sistema se conoce como muestreo y permite superar estos baches presupuestales para alcanzar resultados cercanos a la realidad.
        .col-lg-2.col-4.order-lg-2.order-1.mb-lg-0.mb-4
          .row.justify-content-center
            .col-lg-8
              img(src="@/assets/curso/tema1/img34.svg")

    p La encuesta puede provenir de dos tipos de fuentes: internas y externas.

    .row.justify-content-center.mb-4
      .col-xl-5.col-lg-6.col-md-10.mb-xl-0.mb-4(data-aos="fade-right")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/tema1/img35.jpg' alt='AvatarTop')
          .tarjetas-up_card.BG03.p-xl-4.p-3
            .title.d-flex.justify-content-between.align-items-center.mb-md-4.mb-3
              h4.mb-0 Fuentes internas
              span
                i.fas.fa-chevron-circle-up.fa-2x.me-3
                i.fas.fa-chevron-circle-down.fa-2x.me-3
            p.mb-0 Cuando la encuesta proviene de fuentes internas, como empleados, directivos o propietarios, es posible acceder a todos ellos y consultarles de forma directa para lograr resultados consolidados fidedignos y sin un margen de error apreciable.
      .col-xl-5.col-lg-6.col-md-10(data-aos="fade-left")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/tema1/img36.jpg' alt='AvatarTop')
          .tarjetas-up_card.BG03.p-xl-4.p-3
            .title.d-flex.justify-content-between.align-items-center.mb-md-4.mb-3
              h4.mb-0 Fuentes externas
              span
                i.fas.fa-chevron-circle-up.fa-2x.me-3
                i.fas.fa-chevron-circle-down.fa-2x.me-3
            p.mb-0 Esta situación no se replica para las fuentes de información externas, por ejemplo, si se consulta a los proveedores es posible que no todos tengan disponibilidad o voluntad de responder o en el caso de los clientes, puede que el producto tenga un alcance tan amplio que el número total de clientes sea inmanejable.

    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-lg-10.BG06.mb-4
        .row.justify-content-center.align-items-end
          .col-lg-4.col-8
            img(src='@/assets/curso/tema1/img37.png')
          .col-lg-8.p-4
              .row.mb-4
                .col-auto.BG02.p-2
                  .h5.text-primario.mb-0 Entonces, ¿cuál puede ser una buena forma de realizar las encuestas?
              p.text-white.mb-0 El muestreo es la herramienta que hace posible la recolección de esta información sin necesidad de acudir a la totalidad de los sujetos. por ejemplo, para saber de qué fruta está hecha una bebida no hace falta beberla toda, con un pequeño sorbo se puede intuir el componente principal de todo el contenido. De esta misma forma funciona la muestra, con un grupo significativo que pertenece a una población mayor se puede tener resultados muy cercanos a los que se obtendrían consultándolos a todos.

    p El sistema de muestreo puede ser tan improvisado o estructurado como se desee. Si se trata de análisis administrativos en las empresas no existen requerimientos mínimos o máximos para llevar a cabo el trabajo, estas imposiciones son expresadas por los directivos interesados en los resultados. Situación diferente se da en el ámbito social o público, en el que las fichas técnicas en las que se listan los detalles de las encuestas deben cumplir con unos estándares técnicos que brinden una mayor credibilidad al ejercicio. 
    p Para adentrarse un poco más en el proceso de estimación de una muestra objetiva y que cumpla con los requisitos propios de un trabajo sistemático se presentan algunas de las metodologías más utilizadas con una breve reseña de su mecánica: 

    .row.justify-content-center.mb-4(data-aos="zoom-in")
      AcordionA.mb-5(tipo="a" clase-tarjeta="BGIMG01")
        .row.justify-content-center(titulo="Muestreo Aleatorio Simple (MAS)")
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img38.png')
          .col-lg-6
            p.mb-0 Bajo este sistema, todos los individuos que conforman una población tienen el mismo valor, así que cuentan con las mismas probabilidades de ser elegidos en la muestra. Como su nombre lo indica, los individuos son elegidos al azar, por ejemplo, si se quiere saber cuántos hombres o mujeres ingresan a la tienda a consultar los productos, todos los clientes tienen el mismo valor en la población.
        .row.justify-content-center(titulo="Muestreo Aleatorio Estratificado (MAE)")
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img39.png')
          .col-lg-6
            p.mb-0 Cuando se evalúan más variables se pueden dar situaciones en las que los individuos puedan pertenecer a subgrupos, sobre los cuales se espera tener una participación equitativa, por ejemplo, si se evalúa el ambiente laboral de una empresa que tiene varias sedes administrativas y comerciales alrededor del país se espera que la muestra seleccione individuos de cada una para lograr un resultado más integral. Una forma práctica de hacerlo es definir la muestra en cada una de las sedes de forma independiente y luego consolidar todo en un estudio global.
        .row.justify-content-center(titulo="Muestreo Sistemático (MS)")
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img40.png')
          .col-lg-6
            p.mb-0 Este método acude a patrones a partir de los cuales se listan los participantes de la muestra. Existen muchas posibilidades y será criterio de quien elabore el trabajo, elegir cuál se adapta mejor a la naturaleza del estudio. A modo de ejemplo, se puede plantear una situación en la que se listan todos los individuos objeto de investigación y se determina que, para esa muestra, será tomado uno de cada cinco.
        .row.justify-content-center(titulo="Muestreo no probabilístico")
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img41.png')
          .col-lg-6
            p.mb-0 A diferencia de los sistemas anteriores, en este se obvia el azar a la hora de la escogencia de los individuos. Se realiza la selección de forma consciente, eligiendo cada persona de forma independiente. Al obedecer a la opinión del investigador, puede crear sesgos debido a la posición que tome el entrevistador, por ejemplo, trabajar con los empleados históricamente más problemáticos, los clientes que han interpuesto quejas o reclamos, o los proveedores que dependen de la empresa para mantenerse en el mercado, son situaciones que pueden llevar a conclusiones cuestionables.

    p Además del sistema de selección es importante determinar con qué proporción del total de la población se satisfacen las exigencias del estudio. Elegir el tamaño apropiado de la muestra para alcanzar estos objetivos puede ser tan complejo y preciso como se desee. A continuación se presentan los elementos clave a tener en cuenta: 

    figure.mb-4(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    p La encuesta es una de las metodologías de recolección de información de mayor facilidad de uso y practicidad en la actualidad; su aplicación tiene relevancia tanto en ambientes productivos y organizacionales, como en estudios académicos, sociales o económicos; lo anterior sustentado en su viabilidad para abordar poblaciones de tamaño considerable.
    p.mb-5 Para lograr consolidar las respuestas obtenidas resulta especialmente recomendable hacer uso de sistemas de consolidación de información como la elaboración de tablas donde se presenten los individuos en las filas y las respuestas en las columnas. Para que este trabajo sea posible es importante que las preguntas sean cerradas y respondan a un número, carácter o rango. 

    .row.justify-content-center.mb-4
      .col-lg-10.cajon.color-secundario.p-4.mb-4(data-aos="flip-up")
        p.mb-0 Esta mecánica se conoce como tabulación y consiste en cambiar el formato de la información a tablas, especialmente útil con grandes cantidades de datos apilables según criterios.
      .col-lg-10
        p.text-center Para comprender mejor su funcionamiento es necesario entender dos conceptos básicos:
      
    .row.justify-content-center.mb-5
      .col-xl-5.col-lg-6.col-md-10.mb-xl-0.mb-4(data-aos="fade-right")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/tema1/img42.jpg' alt='AvatarTop')
          .tarjetas-up_card.BG03.p-xl-4.p-3
            .title.d-flex.justify-content-between.align-items-center.mb-md-4.mb-3
              h4.mb-0 Frecuencia absoluta
              span
                i.fas.fa-chevron-circle-up.fa-2x.me-3
                i.fas.fa-chevron-circle-down.fa-2x.me-3
            p.mb-0 Consiste en el conteo de las respuestas para la variable, es decir, el número de personas que fueron abordadas con una misma pregunta. Su valor se expresa en números naturales o absolutos, es decir, 1, 10 o 100 personas.
      .col-xl-5.col-lg-6.col-md-10.mb-xl-0.mb-4(data-aos="fade-left")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/tema1/img43.jpg' alt='AvatarTop')
          .tarjetas-up_card.BG03.p-xl-4.p-3
            .title.d-flex.justify-content-between.align-items-center.mb-md-4.mb-3
              h4.mb-0 Frecuencia relativa
              span
                i.fas.fa-chevron-circle-up.fa-2x.me-3
                i.fas.fa-chevron-circle-down.fa-2x.me-3
            p.mb-0 Mide la proporción de participantes que dieron una respuesta en concreto a la variable consultada. Se mide en porcentajes, por lo que, si la mitad de las personas respondieron sí, y la otra mitad no, las frecuencias relativas serían del 50 % para cada respuesta.

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-10.mb-4
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/img44.svg')})`}"
          )(data-aos="fade-right")
          .bloque-texto-g__texto.p-4(data-aos="fade-left")
            p.mb-0 Para que la creación de intervalos resulte pertinente se recomienda que sean excluyentes, es decir, que una respuesta no pueda estar en más de un intervalo a la vez, y que todas las respuestas encajen dentro de una de las categorías, evitando así, respuestas huérfanas que no tengan dónde tabularse.

    p Estos intervalos obedecen a la opinión de quien lleva a cabo el trabajo, por lo que puede variar según criterios; en la medida de lo posible se recomiendan intervalos que sean parejos, de tal forma que cada uno agrupe un mismo rango de respuestas posibles. Esta situación no es imperativa, ya que en ciertos análisis puede resultar más conveniente el uso de intervalos irregulares con aplicación práctica. Para entender mejor, vea el siguiente ejemplo: 
    p.mb-5 Si la consulta en concreto es sobre la edad promedio de los clientes, los intervalos irregulares, según los sistemas demográficos, podrían ser más útiles. A continuación, se presenta una tabla en la que se resumen los resultados de una encuesta en la que se consultó la edad a cien personas:

    .row.justify-content-center.mb-4
      .col-lg-10
        .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
          h5 Tabla 2
          span Tabulación de datos cuantitativos

        .tabla-a.color-acento-botones.mb-5(data-aos="zoom-in")
          table
            thead(style="border-color: #DAE27F")
              tr
                th(style="background-color: #DAE27F; width: 60 %").text-center Variable
                th(style="background-color: #DAE27F; width: 20 %").text-center Frecuencia absoluta
                th(style="background-color: #DAE27F; width: 20 %").text-center Frecuencia relativa
            tbody
              tr
                td(style="background-color: #E8F2F6;").text-center.text-bold Menores de 18 años
                td(style="background-color: #E8F2F6;").text-center 27
                td(style="background-color: #E8F2F6;").text-center 27 %
              tr
                td.text-center.text-bold Mayores de 18 y menores de 60 años
                td.text-center 53
                td.text-center 53 %
              tr
                td(style="background-color: #E8F2F6;").text-center.text-bold Mayores de 60 años
                td(style="background-color: #E8F2F6;").text-center 20
                td(style="background-color: #E8F2F6;").text-center 20 %
              tr
                td.text-center.text-bold Total de encuestados
                td.text-center 100
                td.text-center 100 %
    
    separador
    #t_1_5.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.5 Análisis de contenido

    .BGM01.px-md-5.px-4
      .row.justify-content-center.align-items-center.mb-4
        .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
          p Como última metodología se presenta el análisis de contenido, vea en qué consiste:
          p El análisis de contenido consiste en la recolección y análisis de datos de forma paralela; las fuentes de información suelen ser documentos elaborados por terceros en un área específica, por lo que la parte de apropiar los datos directamente del entorno no tiene la prioridad como en las metodologías anteriores. 
          p.mb-0 Esta metodología es un buen complemento a la de la observación, puesto que hay situaciones que pueden haberse estudiado previamente, por lo que el análisis de contenido permite comparar resultados históricos con los actuales. 
        .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
          img(src="@/assets/curso/tema1/img45.png")

      .row.justify-content-center.mb-4
        .col-lg-10.BG03(data-aos="flip-up")
          .row.justify-content-center
            .col-lg-1.col-2.order-1
              img(src="@/assets/curso/tema1/img46.svg")
            .col-lg-10.order-lg-2.order-3
              .p-4
                p.mb-0 Si se indaga sobre los niveles de producción en una planta que funciona un número determinado de horas, se puede establecer una ratio de unidades producidas por hora de trabajo, que puede compararse con este mismo indicador de años anteriores: Así se puede evaluar si la maquinaria ha disminuido su productividad por temas de obsolescencia, daños u otras condiciones.
            .col-lg-1.col-2.order-lg-3.order-2
              img.img01(src="@/assets/curso/tema1/img47.svg")
      
      p Este sistema permite dar continuidad a procesos o sistemas de evaluación que fueron iniciados en el pasado, así se consigue progresar en términos de conocimiento o buenas prácticas. Situación muy común en ambientes productivos, por ejemplo, cuando se busca mejorar una receta utilizada en la elaboración de algún bien. Así es como las marcas toman una fórmula base y a través de modificaciones ofrecen productos diferentes. Este es el caso de empresas como Coca-Cola con su versión sin azúcar, o con sabor a café, su base sigue siendo la misma: pero, con ligeros ajustes que diversifican su oferta. 
      p Este sistema también facilita el análisis comparativo, que es de vital importancia en las organizaciones, puesto que permite efectuar dos evaluaciones de un mismo proceso o actividad, separadas por una ventana de tiempo y medir así su evolución. Por otra parte, se pueden hacer análisis con otras empresas para determinar si las estrategias utilizadas son más o menos productivas que las de la competencia, esta práctica cuenta con gran aceptación a nivel empresarial y es conocida como benchmarking.

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-lg-10.BG03.p-4
        .row.justify-content-center
          .col-lg-3.col-6
            img(src="@/assets/curso/tema1/img48.svg")
          .col-lg-9
            p La información por comparar puede ser de naturaleza cuantitativa o cualitativa. 
            ul.lista-ul--color
              li
                <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
                p.mb-0 En los #[b datos cuantitativos] existe una mayor objetividad en cuanto a la evidencia, ya que las cifras en sí mismas permiten determinar variaciones positivas o negativas sin mayor trabajo. 
              li
                <i class="fas fa-circle" style="color:#F3AB1D; font-size: x-small"></i>
                p.mb-0 Caso contrario con la #[b información cualitativa], puesto que al tratarse de datos descriptivos y, por tanto, abiertos a una interpretación, el criterio del analista puede diferir de los juicios que emitiría otro.
    
    p Durante la ejecución del análisis de contenido lo más recomendable es desarrollar el trabajo cumpliendo con las siguientes tres fases:

    .row.justify-content-center.mb-4
      .col-lg-10.BGIMG02.p-4(data-aos="zoom-in")
        SlyderA(tipo="b")
          .row.justify-content-center.align-items-center
            .col-lg-6.order-lg-1.order-2
              .h4 Planeación
              p.mb-0 En primer lugar, se debe definir el objetivo de la investigación o auditoría a realizar, tener una imagen clara de la problemática o situación que se espera abordar y por la cual se motiva la recolección de la información. Es aconsejable elaborar un listado de las actividades a realizar, de tal forma que, si se espera replicar el ejercicio en periodos futuros, se pueda minimizar las diferencias en el proceso.
            .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
              img(src="@/assets/curso/tema1/img49.png")
          .row.justify-content-center.align-items-center
            .col-lg-6.order-lg-1.order-2
              .h4 Explotación del material
              p.mb-0 Con el alistamiento previo, es posible iniciar la indagación y consulta del contenido existente, bien sea el histórico de la propia entidad o el comparativo de otras empresas que operan en el mismo sector. Los datos relevantes que se vayan obteniendo deben ser registrados como evidencia de las futuras conclusiones. Es importante diseñar una hoja de instrucciones que describa la mecánica de la metodología aplicable al trabajo. Así, se deben definir por ejemplo las escalas de medición que se utilizarán, el tamaño de la muestra si aplica o el vocabulario con términos técnicos que hace falta tener presentes en el estudio.
            .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
              img(src="@/assets/curso/tema1/img50.png")
          .row.justify-content-center.align-items-center
            .col-lg-6.order-lg-1.order-2
              .h4 Tratamiento de la información
              p.mb-0 Finalmente, se debe consolidar la información obtenida y efectuar la interpretación del contenido. En esta fase se presentan los resultados obtenidos con las justificaciones del caso, así como las propuestas sobre las acciones para solucionar la problemática expuesta en la primera fase.
            .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
              img(src="@/assets/curso/tema1/img51.png")

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    modal1: false,
    mostrarIndicador: true,
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
