<template>
  <section class="container">
    <div>
      <nuxt-link to="/">
        <app-logo/>
      </nuxt-link>
      <hr>
      <h1 class="title">
        Requacifin
      </h1>
      <h2 class="subtitle">
        Esta página vamos a indexarla e intentar posicionarla para la keyword inventada Requacifin
      </h2>
      <app-content/>
      <div class="static-content">
        <p>Actualmente no existe ningún resultado en Google para la keyword <strong>Requacifin</strong>, así que el objetivo será no solo indexar esta página si no que aparezca en resultados de búsqueda.</p>
        <p>Desde esta página, vamos a enlazar a otra subpágina a indexar y posicionar por otra keyword inventada:</p>
          <nuxt-link to="/wekilinest" class="button--green">Wekilinest</nuxt-link>
          <p>El 19 de julio de 2018 abrimos el archivo robots.txt para permitir que los bots rastreen e indexen esta página. ¿Cuánto tardará Google en rastrearla e indexarla? Al tratarse de un Server Side Rendering, debería realizar una indexación mucho más rápida que para las las opciones SPA y Static.</p>
          <p>¿Los resultados? Los veremos a partir del 27 de julio ;) </p>
          <p>Recuerda que puedes navegar entre las otras versiones del experimento desde https://pwaexperiments.com</p>
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
        title: 'Requacifin',
        meta: [
          { hid: 'description', name: 'description', content: 'En esta página trabajamos la keyword inventada Requacifin para comprobar la indexación de contenidos en buscadores de una SSR PWA.' },
          { hid: 'og:title', name: 'og:title', content: 'Requacifin' },
          { hid: 'og:description', name: 'og:description', content: 'En esta página trabajamos la keyword inventada Requacifin para comprobar la indexación de contenidos en buscadores de una SSR PWA.' }
        ]
      }
    }
}
</script>
