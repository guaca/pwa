<template>
  <section class="container">
    <div>
      <nuxt-link to="/">
        <app-logo/>
      </nuxt-link>
      <hr>
      <h1 class="title">
        Kicalithno
      </h1>
      <h2 class="subtitle">
        Esta página vamos a indexarla e intentar posicionarla para la keyword inventada Kicalithno
      </h2>
      <app-content/>
      <div class="static-content">
        <p>Actualmente no existe ningún resultado en Google para la keyword inventada <strong>Kicalithno</strong>, así que el objetivo será no solo indexar esta página si no que aparezca en resultados de búsqueda.</p>
        <p>El 19 de julio abrimos el robots.txt para permitir a los bots el rastreo e indexación de este subdominio. ¿Cuánto tardará Google en rastrearla e indexarla? Al tratarse de un SSR, debería realizar una indexación mucho más rápida que para las las opciones SPA y estática pese a ser una página que está en segundo nivel de profundidad.</p>
        <p>¿Los resultados? Los veremos a partir del 27 de julio ;) </p>
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
        title: 'Kicalithno',
        meta: [
          { hid: 'description', name: 'description', content: 'En esta página trabajamos la keyword inventada Kicalithno para comprobar la indexación de contenidos en buscadores de una SSR PWA.' },
          { hid: 'og:title', name: 'og:title', content: 'Kicalithno' },
          { hid: 'og:description', name: 'og:description', content: 'En esta página trabajamos la keyword inventada Kicalithno para comprobar la indexación de contenidos en buscadores de una SSR PWA.' }
        ]
      }
    }
}
</script>
