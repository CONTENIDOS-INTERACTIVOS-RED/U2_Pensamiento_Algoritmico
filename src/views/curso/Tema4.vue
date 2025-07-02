<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(:titulo="'Unidad 2. Algoritmos y la Revolución 4.0'" :subTitulo="'SÍNTESIS'")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      
      p(data-aos="fade-up").mb-4 Desde la automatización de procesos hasta la inteligencia artificial y el análisis de datos, los algoritmos se han convertido en el núcleo de la Revolución 4.0. En esta unidad, descubrirá cómo los algoritmos impactan la industria moderna, potenciando la eficiencia, reduciendo errores y transformando el entorno laboral. Exploraremos su aplicación en tecnologías avanzadas como el Big Data y el Internet de las Cosas (IoT), destacando cómo estas herramientas permiten la toma de decisiones basada en datos y optimizan los procesos sin intervención humana.

      p.mb-5 #[strong ¡Prepárese para comprender y aplicar los principios del pensamiento algorítmico en el contexto de la era digital!]



      .row.justify-content-center
        .col-lg-12.mb-5
          figure.bg-color-sintesis.p-5.brounded
            img(src='@/assets/curso/sintesis/sintesis.svg', alt='', style="max-width: 1240px;")
  </template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    // variables de vue
  }),
}
</script>
