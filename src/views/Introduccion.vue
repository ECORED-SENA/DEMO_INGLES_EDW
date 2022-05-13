<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
        
   
      .subtitulo-guion.mt-5
        h2#actividad-1  Actividad de speaking
      .row.align-items-center.justify-content-center.my-5
        .col-8.col-md-4
          figure
            img.img-fluid(src='@/assets/componentes/img_actividad.svg' alt='')
        .col-12.col-md-8
          .px-2
            p
              | Demo de actividad didáctica de reconocimiento de voz, a través del API Web Speech desarrollada para Google Chrome y Mozilla Firefox.
            p
              | Haz clic en el botón Start para abrir la actividad.
            a.boton.boton--b(:href="obtenerLink('/actividades/phrase-matcher/index.html')" target="_blank")
                span Start
                i.fas.fa-puzzle-piece
      hr.line-100.bg-orange.my-5

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
