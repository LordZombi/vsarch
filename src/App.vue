<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="less">
@import '~normalize.css';
@import './less/variables';

#app {
  font-family: 'Roboto Condensed', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-weight: 300;
}

body {
  font-size: 14px;

  @media (min-width: @break-m-min) {
    font-size: 16px;
  }

  @media (min-width: @break-t-min) {
    font-size: 24px;
  }
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: 300;
}

h1 {
  font-size: 2em;

  @media (min-width: @break-t-min) {
    font-size: 2.1em;
  }
}

h2 {
  font-size: 2em;
  text-align: center;

  @media (min-width: @break-t-min) {
    font-size: 2.1em;
  }
}

h3 {
  font-size: 1.1em;

  @media (min-width: @break-t-min) {
    font-size: 1.3em;
  }
}
</style>
