<template lang="pug">
  .about
    h1 This is the deck view for deck {{ $route.params.id }}
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
