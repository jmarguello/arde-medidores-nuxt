<template>
  <div>
    <nuxt-link :to="switchLocalePath('en')">English</nuxt-link>
    <nuxt-link :to="switchLocalePath('es')">Español</nuxt-link>
    <nuxt-link :to="switchLocalePath('fr')">Français</nuxt-link>
    <br /><br />

    <h1>{{ $t('hola') }}</h1>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
