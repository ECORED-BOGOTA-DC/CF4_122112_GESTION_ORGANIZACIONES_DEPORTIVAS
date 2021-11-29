<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Mecanismos de control y evaluación del proyecto 
    
    .row
      .col-md-7.mb-4(data-aos="fade-right")
        p En los proyectos son necesarios los mecanismos que permitan su control y evaluación, pues controlar un proyecto consiste en medir el avance real y compararlo periódicamente con el avance previsto en el plan. La fase de planeación es de gran importancia porque 
          strong brinda una ruta y direcciona el proyecto. 
          | Sin embargo, no se puede pretender que el plan se cumpla a cabalidad sin establecer algún tipo de control sobre este, por lo anterior, realizar un proyecto sin un control, será exponerse a una constante incertidumbre, sin saber si se está ejecutando acorde a lo esperado, por debajo de lo esperado o incluso más rápido a lo esperado. 
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1-img.png', alt='Mecanismos de control y evaluación del proyecto ')

    p.mb-4(data-aos="fade") El control abarca no solo el cumplimiento del cronograma en el tiempo, sino también con los recursos dispuestos para su ejecución. Por ello, el control se considera un proceso que comprende tres acciones principales:

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-md-10
        PasosA.color-acento-contenido(tipo="n")
          .row.justify-content-center.align-items-center
            .col-md-3.col-8.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema1-linea1-ico1.svg', alt='Texto que describa la imagen')
            .col-md-8
              h5 Medir el progreso hacia el objetivo preestablecido.
          .row.justify-content-center.align-items-center
            .col-md-8.mb-4.mb-md-0
              h5 Evaluar lo que se requiere para alcanzar los objetivos.
            .col-md-3.col-8
              figure
                img(src='@/assets/curso/tema1-linea1-ico2.svg', alt='Texto que describa la imagen')
          .row.justify-content-center.align-items-center
            .col-md-3.col-7.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema1-linea1-ico3.svg', alt='Texto que describa la imagen')
            .col-md-8
              h5 Aplicar acciones correctivas para alcanzar o superar lo proyectado.   
        
    p.mb-4(data-aos="fade")  Son muchas las situaciones que pueden acontecer durante la ejecución del proyecto que impidan o faciliten el cumplimiento del plan, por lo que el control cobra especial importancia para asegurarse de que todo marche según lo estipulado; es decir, 
      strong  medir el avance real y compararlo con el avance previsto. 
      | Un insumo fundamental para el control del proyecto será el 
      strong cronograma de actividades, 
      | en donde se debe tener certeza sobre:

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-md-10
        PasosA.color-acento-contenido(tipo="n")
          .row.justify-content-center.align-items-center
            .col-md-3.col-8.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema1-linea2-ico1.svg', alt='Texto que describa la imagen')
            .col-md-8
              p ¿Cuándo se inician las actividades?
          .row.justify-content-center.align-items-center
            .col-md-8.mb-4.mb-md-0
              p ¿Cómo se están desarrollando?
            .col-md-3.col-8
              figure
                img(src='@/assets/curso/tema1-linea2-ico2.svg', alt='Texto que describa la imagen')
          .row.justify-content-center.align-items-center
            .col-md-3.col-8.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema1-linea2-ico3.svg', alt='Texto que describa la imagen')
            .col-md-8
              p ¿Cuál es la fecha de finalización de las actividades?  


    p(data-aos="fade") Otro aspecto a considerar será la 
      strong periodicidad del control de un proyecto, 
      | la que dependerá de la duración, complejidad y alcance, entre otros. Esta periodicidad podrá ser diaria, semanal, mensual, bimestral, trimestral entre otras frecuencias. 

    p.mb-4(data-aos="fade") A continuación, se presentan algunos ejemplos de periodicidad del control en diferentes tipos de proyectos, aunque cabe aclarar que esta la define cada organización según las necesidades del control que se vaya a realizar. 

    .row.mb-4
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta-flip.color-acento-botones.text-center
          .tarjeta-flip__contenedor.text-white
            .tarjeta-flip__img
              img.mb-3(src='@/assets/curso/tema1-1-tarj1-a.png', alt='Proyectos de obra civil.')
              h4.p-3 Proyectos de obra civil.
            .tarjeta-flip__contenido.bg-tarjeta-flip
              img.mb-3(src='@/assets/curso/tema1-1-tarj1-b.png', alt='Control sobre avances de obra.')
              h4.p-3 Control sobre avances de obra. 
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta-flip.color-acento-botones.text-center
          .tarjeta-flip__contenedor.text-white
            .tarjeta-flip__img
              img.mb-3(src='@/assets/curso/tema1-1-tarj2-a.png', alt='Proceso de gestión del talento humano de una organización.')
              h4.p-3 Proceso de gestión del talento humano de una organización.
            .tarjeta-flip__contenido.bg-tarjeta-flip
              img.mb-3(src='@/assets/curso/tema1-1-tarj2-b.png', alt='Control de actividades ejecutadas vs. las programadas del mes.')
              h4.p-3 Control de actividades ejecutadas vs. las programadas del mes.
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta-flip.color-acento-botones.text-center
          .tarjeta-flip__contenedor.text-white
            .tarjeta-flip__img
              img.mb-3(src='@/assets/curso/tema1-1-tarj3-a.png', alt='Proceso operativo de un club deportivo.')
              h4.p-3 Proceso operativo de un club deportivo.
            .tarjeta-flip__contenido.bg-tarjeta-flip
              img.mb-3(src='@/assets/curso/tema1-1-tarj3-b.png', alt='Desarrollo de eventos, actividades programadas para el trimestre.')
              h4.p-3 Desarrollo de eventos, actividades programadas para el trimestre.
      
    p(data-aos="fade") En el control del proyecto es factible identificar posibles desviaciones del plan en materia de recursos o tiempo. Un error frecuente es pretender que las desviaciones del proyecto se solucionen solas, ya que en el momento de detectar desviaciones en la ejecución del proyecto respecto a lo planeado se deberán establecer acciones correctivas, que consisten en identificar cuál es la mejor alternativa en materia de costo beneficio para encaminar nuevamente las actividades del proyecto al cumplimiento de los objetivos. 

    Separador


    //1.1
    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1  Control de las actividades del proyecto 

    .row
      .col-md-7.mb-4(data-aos="fade-right")
        p Las actividades son un componente fundamental en un proyecto, pues estas comprenden 
          strong un inicio, un final y recursos destinados para su ejecución. 
          | El control de la ejecución de las actividades conforme a lo previsto en el plan es de gran importancia, pues el retraso de alguna de ellas afectará el desarrollo de las actividades sucesoras, así mismo finalizar una actividad antes del tiempo previsto podrá afectar negativamente el desarrollo del proyecto.
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1-1-img.png', alt='Imagen decorativa')  

    p.mb-4(data-aos="fade") Es común escuchar de muchos proyectos que no cumplen con el tiempo previamente estipulado en el alcance inicial, otros generan sobrecostos entre otros problemas que afectan al desarrollo de los proyectos y cumplimientos de los objetivos simplemente por no llevar un adecuado control. Por lo tanto, es importante tener en cuenta los siguientes elementos para establecer control de las actividades: 

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-8
        figure
          img(src='@/assets/curso/tema1-1-figura.svg', alt='Control de las actividades del proyecto')  

    .row.bg-contenido.py-5
      .col-md-7.mb-4(data-aos="fade-right")
        p En caso de detectar posibles actividades con retraso, se deben establecer 
          strong acciones correctivas 
          | para no generar sobrecostos ni retraso en el tiempo. Por lo tanto, se deberá evaluar qué opciones tomar para enrutar el proyecto como:
        ul.lista-ul--color.color-acento-botones.px-5
          li 
            i.fas.fa-check
            | Asignar más recursos para acelerar el desarrollo de una actividad.
          li 
            i.fas.fa-check
            | Asignar más personas con mayor experiencia o más competente para el desarrollo de una actividad.
          li 
            i.fas.fa-check
            | Reducir los tiempos y recursos de otra actividad para asignarle a la actividad crítica sin afectar el desarrollo del proyecto.    
      .col-md-5(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1-1-img2.png', alt='Imagen decorativa')

    Separador


    //1.2
    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2  Control de costos del proyecto

    .row
      .col-md-7.mb-4(data-aos="fade-right")
        p Se entiende como el 
          strong conjunto de procedimientos cuya finalidad se centra en conocer los gastos de las tareas del proyecto y medir las variaciones frente al presupuesto estipulado. 
          | Para lograr el objetivo de ejecutar el proyecto conforme a los recursos planeados, se deberá controlar que las diferentes actividades del proyecto se ejecuten según lo presupuestado; para tal fin se deben seguir los siguientes pasos:
        ul.lista-ul--color.px-5
          li 
            i.fas.fa-check
            | Desglosar cada actividad que conforma el proyecto teniendo claro el presupuesto y costos estimados para su desarrollo.
          li 
            i.fas.fa-check
            | Medir el progreso del proyecto y verificar el porcentaje de cumplimiento. 
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1-2-img.png', alt='Imagen decorativa')

    p.mb-4(data-aos="fade") Lo ideal es que, al transcurrir el proyecto, cada actividad y fase del proyecto se ejecuten conforme a los recursos estimados. En algunos casos, se presentan imprevistos, que alteran los valores presupuestados, implicando sobrecostos o bajos costos. A continuación, se describe en qué consiste cada uno de ellos: 

    TabsD.color-acento-botones(data-aos="fade-down")
      .row.justify-content-center.py-4.py-md-5(titulo="Sobrecostos" :icono="require('@/assets/curso/tema1-2-ico1-a.svg')" :icono2="require('@/assets/curso/tema1-2-ico1-b.svg')")
        .col-md-5
          h4 Sobrecostos
          p En el control de costos es común ver desviaciones que generan sobrecostos, es decir, 
            strong un costo más elevado de lo presupuestado inicialmente. 
          p Ante la aparición de un sobrecosto, se deberán tomar acciones correctivas de menor costo que permitan corregir la desviación y hacer que la suma total de las actividades se ajuste a lo previsto en el presupuesto.
          p Algunas alternativas para el control de sobrecostos son las siguientes:
          ul.lista-ul--color
            li 
              i.fas.fa-check
              | Reducir los recursos de otra actividad, sin que afecte su desarrollo ni la calidad del proyecto.
            li 
              i.fas.fa-check
              | Sustituir productos, servicios, materias primas que presten la misma función requerida en el proyecto y a menor costo.
            li 
              i.fas.fa-check 
              | Asignar personas con mayor experiencia para realizar la actividad de manera más eficiente.  
        .col-md-5
          figure.mb-4
            img(src='@/assets/curso/tema1-2-tab1.png', alt='Sobrecostos')
      .row.justify-content-center.py-4.py-md-5(titulo="Bajo costos" :icono="require('@/assets/curso/tema1-2-ico2-a.svg')" :icono2="require('@/assets/curso/tema1-2-ico2-b.svg')")
        .col-md-5
          h4 Bajo costos
          p No siempre los problemas están asociados exclusivamente a los sobrecostos. En el otro extremo, los bajos costos podría indicar que 
            strong no se está ejecutando correctamente el presupuesto del proyecto o alguna de las actividades no se está realizando.
          p Por lo tanto, al detectar un bajo costo se deben evaluar los avances del proyecto conforme a lo previsto en tiempo y recursos.
        .col-md-5
          figure.mb-4
            img(src='@/assets/curso/tema1-2-tab2.png', alt='Bajo costos')

    Separador


    //1.3
    #t_1_3.titulo-segundo.color-acento-contenido
      h2 1.3  Control del riesgo

    p(data-aos="fade") La gestión del riesgo es una medida proactiva que 
      strong permite anticiparse a que una situación adversa ocurra e impida el cumplimiento a cabalidad del proyecto. 
      | En el plan de control de riesgos establecidos se monitorea acerca de su efectividad en la implementación para identificar que se esté logrando el efecto deseado.

    p.mb-4(data-aos="fade") Por medio del seguimiento de los riesgos se verifica que las medidas de control, reduzcan al máximo los riesgos. Si por el contrario, los riesgos se han efectuado o han incrementado, e incluso han surgido nuevos riesgos, se deberán replantear nuevas estrategias para su control. Para tal fin se siguen estos pasos:

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-8
        figure
          img(src='@/assets/curso/tema1-3-figura.svg', alt='Control del riesgo')

    p(data-aos="fade") El control de riesgos es fundamental, ya que, en caso de no hacerlo, podrá poner en riesgo el desarrollo del proyecto, generando desde sobrecostos, retrasos hasta la culminación del mismo. 

    Separador


    //1.4
    #t_1_4.titulo-segundo.color-acento-contenido
      h2 1.4  Control de la calidad

    p.mb-4(data-aos="fade") Los proyectos asociados a organizaciones deportivas, generalmente se enfocan en la prestación de servicios mediante la oferta de programas deportivos, actividad física y recreación. En la fase de planeación se han preestablecido los requerimientos de calidad que deben contar los servicios ofertados. Por lo tanto, en esta fase de control, 
      strong se monitorea que estos requerimientos se estén cumpliendo de acuerdo en lo planteado de manera inicial.

    .row.justify-content-center(data-aos="fade-down")
      .col-md-10
        .bloque-texto-g.color-acento-contenido.custom-cardBlock.p-3.p-sm-4.p-md-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1-4-bloque.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Al referirse a una empresa que fabrica zapatos, el control de calidad tendría que avalar que el calzado cumpla con las especificaciones indicadas como peso, color, material, dimensiones, entre otros detalles establecidos en su fase de diseño. En el caso de las organizaciones deportivas, en estas se establecen, conforme a sus servicios, cuáles son sus 
              strong parámetros de control de calidad 
              | como la 
              strong prestación del servicio 
              | y el 
              strong cumplimiento de procedimientos 
              | y 
              strong protocolos preestablecidos. 

    Separador


    //1.5
    #t_1_5.titulo-segundo.color-acento-contenido
      h2 1.5  Informes de gestión 

    p.mb-4(data-aos="fade") El objetivo es comunicar a las partes interesadas sobre el desempeño organizacional, el estado del proyecto y si se encuentra o no encaminado al cumplimiento de los objetivos conforme a lo establecido en el plan. Por ello, los informes de gestión deben ser breves, concisos y concretos para obtener retroalimentaciones ágiles y aplicar posibles acciones correctivas oportunamente. En el informe se deberán presentar los siguientes aspectos:
    
    ImagenInfografica.color-acento-botones
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema1-5-info.jpg', alt='Informes de gestión')

      .tarjeta.row.img-infog.bg-white1.align-items-center(x="81%" y="18%")
        .col-md-4
          img(src='@/assets/curso/tema1-5-ico1.svg', alt='Icono decorativo')
        .col-md-8.contenido.px-4
          p.mb-0 Conclusiones y recomendaciones siempre enfocadas al cumplimiento de los objetivos.

      .tarjeta.row.img-infog.bg-white1.align-items-center.contenido-120(x="70%" y="34%")
        .col-md-4
          img(src='@/assets/curso/tema1-5-ico2.svg', alt='Icono decorativo')
        .col-md-8.px-4
          p.mb-0 Desviaciones en la ejecución de actividades conforme al plan.    

      .tarjeta.row.img-infog1.bg-white1.align-items-center(x="48%" y="59%")
        .col-md-4
          img(src='@/assets/curso/tema1-5-ico3.svg', alt='Icono decorativo')
        .col-md-8.contenido.px-4
          p.mb-0 Porcentaje de ejecución de actividades conforme a lo planeado en materia de tiempo, costos y calidad.

      .tarjeta.row.img-infog.bg-white1.align-items-center.contenido-120(x="36%" y="75%")
        .col-md-4
          img(src='@/assets/curso/tema1-5-ico4.svg', alt='Icono decorativo')
        .col-md-8.px-4
          p.mb-0 Informe de ejecución del proyecto.  



    Separador


    //1.6
    #t_1_6.titulo-segundo.color-acento-contenido
      h2 1.6  Evaluación del proyecto

    p.mb-4(data-aos="fade") Todo proyecto debe tener un cierre o una fase final que le dará paso al inicio de la próxima fase o, incluso, un nuevo proyecto. En esta fase se determina el nivel de eficacia y efectividad del proyecto en materia de cumplimiento de los objetivos conforme el alcance, recursos y tiempo presupuestado, pues la evaluación deberá integrar cada una de las partes interesadas del proyecto, como: personas que trabajaron en el proyecto, clientes, proveedores, patrocinadores, entre otros actores que tuvieron algún tipo de relación o interés en el proyecto. La evaluación podrá ser de diferentes tipos como se menciona a continuación:     

    TabsA.color-acento-contenido
      .row.tarjeta.bg-acento-contenido2.p-4(titulo="Autoevaluación")
        .col-md-6
          h4 Autoevaluación
          p Construida y ejecutada por personas que laboraron en el proyecto, en la que se identifican el cumplimiento de los objetivos, éxitos y aspectos por mejorar.
        .col-md-6
          img(src='@/assets/curso/tema1-6-tab1.png', alt='Autoevaluación')
      .row.tarjeta.bg-acento-contenido2.p-4(titulo="Evaluación interna")
        .col-md-6
          h4 Evaluación interna
          p Evaluación aplicada por personas que trabajan en la organización, pero que no intervinieron en el proyecto.
        .col-md-6
          img(src='@/assets/curso/tema1-6-tab2.png', alt='Evaluación interna')
      .row.tarjeta.bg-acento-contenido2.p-4(titulo="Evaluación externa")
        .col-md-6
          h4 Evaluación externa
          p Personas externas a la organización y al proyecto, contratadas para evaluar el rendimiento del proyecto. 
        .col-md-6
          img(src='@/assets/curso/tema1-6-tab3.png', alt='Evaluación externa')        




</template>

<script>
import TabsD from '../components/TabsD'
export default {
  name: 'Tema1',
  components: {
    TabsD,
  },
  data: () => ({
    // variables de vue
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
