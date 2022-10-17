<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="https://ouch-cdn2.icons8.com/YgRLf-XEY2hwi_tuKT-qDRJ46RcEVYbJCCKeXGTGQO0/rs:fit:357:456/czM6Ly9pY29uczgu/b3VjaC1wcm9kLmFz/c2V0cy9wbmcvNjk2/LzA0NTBmNTI5LTI4/NGEtNDhlMy1iMWZm/LTZjOGY2NWFkYTVh/YS5wbmc.png" width="200" height="200" />

    <div class="wrapper">
      <HelloWorld msg="Buat Pengingat Aja!" />
    </div>
  </header>

  <main>
    <TheWelcome />
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
