<template>
  <div>
    <nuxt/>
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

p {
  padding: 6px;
  margin: 10px 0;
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
  margin: 20px 15px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.container {
  justify-content: center;
  align-items: center;
  text-align: center;
  align-self: flex-start;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 400;
  font-size: 50px;
  color: #35495e;
  letter-spacing: 1px;
  margin: 10px 100px;
}

.subtitle {
  font-weight: 500;
  font-size: 28px;
  color: #526488;
  word-spacing: 5px;
  padding: 15px 0;
  margin: 20px 100px;
}

.links {
  padding-top: 15px;
}

.static-content{
  font-size: 22px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  margin: 0 20px;
}

hr {
    background-image: linear-gradient(20deg, #46B784, #5A21C5);
    height: 5px;
}

@media screen and (max-width: 992px) {
  .title {
    font-size: 30px;
    font-weight: 500;
    margin: 10px 30px;
  }
  .subtitle {
    font-size: 20px;
    margin: 10px 30px;
    font-weight: 500;
  }

  .static-content{
    font-size: 18px;
  }
}

</style>
