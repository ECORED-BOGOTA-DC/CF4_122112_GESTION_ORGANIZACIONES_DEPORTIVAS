<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Plan de mejora

    .row
      .col-md-7.mb-4(data-aos="fade-right")
        p Para que todo proyecto u organización evolucione y mejore en el tiempo, se deberán identificar continuamente los aspectos a mejorar y establecer acciones para lograrlo, ya que cada vez existe más competencia, y los productos y servicios son más especializados y gracias a la tecnología los clientes tienen mayor acceso al mercado. Este poder de decisión que tienen los clientes los convierte ahora en protagonistas, a diferencia de hace algunos años que eran actores pasivos acogiéndose a lo que el mercado les ofreciera
        p Ahora 
          strong el cliente, 
          | al tener una oferta tan amplia en el mercado, es quien decide cómo, cuándo y dónde desea sus productos o servicios. El cliente ha adquirido gran poder en la toma de decisiones y esto es un aspecto que las organizaciones deberán tener en cuenta si desean seguir siendo competitivas. Para tal fin, las organizaciones deberán buscar altos estándares de calidad y esto se logra mejorando continuamente sus procesos.
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema2-img.png', alt='Plan de mejora')  
   
    p.mb-4(data-aos="fade") Esto daría cumplimiento al principio de mejora continua en donde siempre en alguna fase, periodo, proceso o servicio, se encontrarán oportunidades las que deberán ser gestionadas para estar en continuo mejoramiento.

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-10
        .bloque-texto-g.color-acento-contenido.custom-cardBlock.p-3.p-sm-4.p-md-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2-bloque.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 El 
              strong plan de mejora 
              | es un proceso que se utiliza para alcanzar la calidad total y mejora de las organizaciones de manera progresiva, y obtener resultados eficientes y eficaces. El punto clave del plan de mejora es 
              strong conseguir una relación entre los procesos y el personal generando una sinergia que contribuya al progreso constante.

    p.mb-4(data-aos="fade") Para trabajar a partir de los planes de mejora, es importante reconocer cuáles son los componentes para generar su impacto:

    .video.mb-4(data-aos="fade-down")
      iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    p(data-aos="fade") Todos los procesos son susceptibles de mejora por más funcionales y exitosos que sean; y para tal fin existen varios métodos en los que el equipo de trabajo identifica los aspectos a mejorar. Uno de los métodos más populares para esta tarea, es la matriz DOFA, que permite establecer fortalezas, debilidades, amenazas y oportunidades. Para entender un poco más, se definirá, explicará su metodología y se realizará ejercicio práctico. 

    p.mb-4(data-aos="fade") La matriz DOFA (Debilidades, Oportunidades, Fortalezas y Amenazas), permite hacer un diagnóstico integral del proyecto desde los aspectos internos (fortalezas y debilidades) y los aspectos externos (oportunidades y amenazas). A continuación, se definen cada uno de los aspectos que integran la matriz DOFA.



</template>

<script>
export default {
  name: 'Tema2',
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
