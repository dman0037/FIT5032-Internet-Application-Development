<script setup>
<<<<<<< HEAD
import JSON from './components/JSON.vue'
=======
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import MyName from './components/MyName.vue'
>>>>>>> 3aa3ab66b22dcf8b7db3bb14ea8ca5d9d2074078
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
<<<<<<< HEAD
    <JSON />
=======
    <TheWelcome />
    <MyName />
>>>>>>> 3aa3ab66b22dcf8b7db3bb14ea8ca5d9d2074078
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
