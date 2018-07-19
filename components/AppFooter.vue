<template lang="html">
  <footer>
    <p>Made with love by <strong>Estela Franco</strong></p>
    <nav>
      <ul>
        <li>
          <a href="https://twitter.com/guaca">Twitter</a>
        </li>
        <li>
          <a href="https://github.com/guaca/pwa">GitHub</a>
        </li>
        <li>
          <a href="https://estelafranco.com">Blog</a>
        </li>
      </ul>
    </nav>
  </footer>
</template>


<style>
  footer {
    position: fixed;
    width: 100%;
    display: flex;
    align-items: center;
    background-image: linear-gradient(20deg, #46B784, #5A21C5);
    color: white;
    font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
    font-weight: 500;
    line-height: 1.5em;
    padding: 10px 30px;
  }
  strong {
    font-size: 20px;
  }
  nav {
      flex-grow: 1;
  }
  ul {
    display: flex;
    justify-content: flex-end;
    list-style-type: none;
    padding-right: 2rem;
  }
  li {
    margin: 12px;
    font-size: 18px;
    padding: 10px 10px;
  }
  a {
    text-decoration: none;
    color: white;
  }

  @media screen and (max-width: 600px) {
    footer {
      align-items: center;
      display: flex;
      flex-direction: column;
      padding: 12px;
      margin-top: 2rem;
    }

    nav {
      display: flex;
      flex-direction: column;
    }
    ul {
      align-items: center;
      display: flex;
      flex-direction: column;
      padding: 0;
    }
    li {
      margin: 0;
      padding: 12px 0px;
    }
  }
</style>
