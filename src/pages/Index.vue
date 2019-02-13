<template>
  <q-page class="flex flex-center">
    {{ apiAtual }}
  </q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'PageIndex',
  data () {
    return {
      apiAtual: process.env.API
    }
  }
}
</script>
