<template>
  <div class="PwaNuxtLogo">
    <img class="nuxt-logo" src="~/assets/images/nuxt-logo.png" alt="nuxt logo">
    <img class="plus-icon" src="~/assets/images/plus-icon.png" alt="plus icon">
    <img class="pwa-logo" src="~/assets/images/pwa-logo.png" alt="pwa logo">
  </div>
</template>

<style>
.PwaNuxtLogo {
  min-height: 4vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.pwa-logo, .nuxt-logo {
  width: 180px;
  margin: 0 20px;
}

.plus-icon {
  padding-right: 10px;
}


@media screen and (max-width: 600px) {
    .pwa-logo, .nuxt-logo {
      width: 30%;
      align-items: center;
      flex-flow: row wrap;
      display: flex;
      padding: 12px;
      margin-top: 2rem;
      nav {
        display: flex;
        flex-direction: column;
      }
    }
    .plus-icon {
      width: 10%;
    }
  }

</style>
