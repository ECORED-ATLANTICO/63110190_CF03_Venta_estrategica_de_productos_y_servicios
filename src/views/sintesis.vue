<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
    .row.justify-content-center.align-items-center.mb-2(data-aos="zoom-in")
      .col-lg-2.col-md-5.mb-4.col-6
        figure
          img(src='@/assets/curso/img_sintesis.svg', alt='Imagen decorativa')
      .col-lg-10.mb-4
        p El componente formativo Fidelización y postventa de productos y servicios se enfoca en fortalecer competencias clave para la atención y permanencia del cliente, mediante el uso de herramientas, estrategias y técnicas orientadas a la fidelización, evaluación de la satisfacción y gestión efectiva de quejas, reclamos y sugerencias, promoviendo así una mejora continua en la experiencia del cliente y relaciones comerciales duraderas desde un enfoque técnico y práctico.

    .row.justify-content-center
      .col-lg-12.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/sintesis.svg", alt="El componente formativo Fidelización y postventa de productos y servicios se enfoca en fortalecer competencias clave para la atención y permanencia del cliente, mediante el uso de herramientas, estrategias y técnicas orientadas a la fidelización, evaluación de la satisfacción y gestión efectiva de quejas, reclamos y sugerencias, promoviendo así una mejora continua en la experiencia del cliente y relaciones comerciales duraderas desde un enfoque técnico y práctico.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
