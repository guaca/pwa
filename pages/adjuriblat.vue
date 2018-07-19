<template>
  <section class="container">
    <div>
      <nuxt-link to="/">
        <app-logo/>
      </nuxt-link>
      <hr>
      <h1 class="title">
        Adjuriblat
      </h1>
      <h2 class="subtitle">
        Esta página vamos a indexarla e intentar posicionarla para la keyword inventada Adjuriblat
      </h2>
      <app-content/>
      <div class="static-content">
        <p>Actualmente no existe ningún resultado en Google para la keyword <strong>Adjuriblat</strong>, así que el objetivo será no solo indexar esta página en Google si no que aparezca en resultados de búsqueda.</p>
        <p>Desde esta página, vamos a enlazar a otra subpágina a indexar y posicionar por otra keyword inventada:</p>
        <nuxt-link to="/kicalithno" class="button--green">Kicalithno</nuxt-link>
        <p>El 19 de julio abrimos el robots.txt para permitir el rastreo e indexación de esta página. ¿Cuánto tardará Google en rastrearla e indexarla? Al tratarse de un proyecto SSR, debería realizar una indexación mucho más rápida que para las las opciones SPA y estática.</p>
        <p>¿Los resultados? Los veremos a partir del 27 de julio ;) </p>
        <p>Recuerda que puedes navegar entre las otras variaciones del experimento desde https://pwaexperiments.com</p>
      </div>
    </div>
    <app-footer/>
  </section>
</template>

<script type="text/javascript">
import AppLogo from '~/components/AppLogo.vue'
import AppFooter from '~/components/AppFooter.vue'

export default {
  components: {
    AppLogo,
    AppFooter
  },
  head () {
      return {
        title: 'Adjuriblat',
        meta: [
          { hid: 'description', name: 'description', content: 'En esta página trabajamos la keyword inventada Adjuriblat para comprobar la indexación de contenidos en buscadores de una SSR PWA.' },
          { hid: 'og:title', name: 'og:title', content: 'Adjuriblat' },
          { hid: 'og:description', name: 'og:description', content: 'En esta página trabajamos la keyword inventada Adjuriblat para comprobar la indexación de contenidos en buscadores de una SSR PWA.' }
        ]
      }
    }
}
</script>
