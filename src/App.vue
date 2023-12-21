<script>
import appHeader from './components/appHeader.vue'

export default {
  components: {
    appHeader
  }
}
</script>

<template>
  <appHeader />
</template>

<style lang="scss">
@use './styles/partials/variable' as *;
@use './styles/general.scss' as *;

h1,
h2,
h3,
h4,
h5,
h6 {
  color: $primary;
}
</style>
