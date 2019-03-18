<template>
  <header>
    <h1>{{ title }}</h1>
    <p>{{ subtitle }}</p>
  </header>
</template>

<script>
export default {
  data() {
    return {
      title: '"Enemy of Boring"',
      subtitle: 'Our Spring Summer 19 collection is an ode to everyone’s inner rebel. Disrupt your boring routines and restore a joyful existence.'
    }
  }
}
</script>

<style scoped lang="scss">
  h1 {
    font-size: 2.4rem;
    text-align: center;
    width: 100%;
    padding-bottom: 0.5rem;
  }
  @include breakpoint(md) {
  p {
    font-size: 0.75rem;
  }
  }
  @include breakpoint(l) {
  h1 {
    font-size: 3rem;
  }
  p {
    font-size: 0.90rem;
  }
  }
</style>
