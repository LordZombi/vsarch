<template>
  <div class="intro">
    <h1 class="intro__title">Ing. arch. Viktória Sabadošová</h1>
    <div class="intro__meta">
      <a href="mailto:viki@vsarch.sk" class="intro__link">viki@vsarch.sk</a>
    </div>
  </div>
</template>

<style lang="less">
@import '../less/variables';

.intro {
  height: 100vh;
  padding: 10px;

  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;

  @media (min-width: @break-t-min) {
    padding: 20px;
  }
}

.intro__link {
  color: #666;
  transition: color .2s;

  &:hover {
    color: #000;
  }
}
</style>
