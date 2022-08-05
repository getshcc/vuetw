<template>
  <section class="p-16">
    <h1 class="text-3xl font-mono font-bold mb-1">Hello {{msg}}</h1>
    <p class="text-slate-400 font-mono text-sm mb-10">Enjoy Developing</p>
    <a href="https://github.com/getshcc" class="text-sm font-mono text-blue-400 hover:text-blue-600">@getShCc</a>
  </section>
</template>

<script>
export default {
  props:["msg"]
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

</style>
