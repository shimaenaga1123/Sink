<template>
  <main class="flex flex-col justify-center">
    <HomeTwitter />
    <HomeHero />
    <HomeFeatures />
    <HomeLogos />
    <HomeCta />
  </main>
</template>

<script>
export default {
  created() {
    // DOM 생성 전에 바로 리다이렉트
    window.location.href = 'https://shimaenaga.dev';
  }
}
</script>
