<template>
  <section class="container">
    <div>
      <nuxt-link to="/">
        <app-logo/>
      </nuxt-link>
      <hr>
      <h1 class="title">
        Wekilinest
      </h1>
      <h2 class="subtitle">
        Esta página vamos a indexarla e intentar posicionarla para la keyword inventada Wekilinest
      </h2>
      <app-content/>
      <div class="static-content">
        <p>Actualmente no existe ningún resultado en Google para la fake keyword <strong>Wekilinest</strong>, así que el objetivo será no solo indexar esta página si no que aparezca en resultados de búsqueda.</p>
        <p>El 19 de julio permitimos a los bots el rastreo e indexación de esta página. ¿Cuánto tardará Google en rastrearla e indexarla? Al tratarse de un SSR, debería realizar una indexación mucho más rápida que para las las opciones SPA y estática a pesar de ser una página en segundo nivel de profundidad.</p>
        <p>¿Los resultados? Los veremos a partir del próximo 27 de julio ;) </p>
        <p>Recuerda que puedes navegar entre las distintas versiones del experimento desde https://pwaexperiments.com</p>
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
        title: 'Wekilinest',
        meta: [
          { hid: 'description', name: 'description', content: 'En esta página trabajamos la keyword inventada Wekilinest para comprobar la indexación de contenidos en buscadores de una SSR PWA.' },
          { hid: 'og:title', name: 'og:title', content: 'Wekilinest' },
          { hid: 'og:description', name: 'og:description', content: 'En esta página trabajamos la keyword inventada Wekilinest para comprobar la indexación de contenidos en buscadores de una SSR PWA.' }
        ]
      }
    }
}
</script>
