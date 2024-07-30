<script setup>
import HelloWorld from './components/HelloWorld.vue'
import StartPage from './components/StartPage.vue';
import TheWelcome from './components/StartPage.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <StartPage></StartPage>
    </div>
  </header>

  <main>
    <p>Wallet</p>
    <div id="ton-connect"></div>

  </main>
</template>

<style scoped>
header {
  line-height: 1.5;

}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
