<template>
  <div id="app">
    <p>Server status: {{ status }}</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      status: 'critical'
    }
  }
}
</script>

<style>

</style>
