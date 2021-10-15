<template>
  <div class="container">
    <h1>Axolotl</h1>
    <img class="img-fluid" v-bind:src="url" />
  </div>

</template>

<script>


const url = "https://media.discordapp.net/attachments/808700312881070120/848290622937759754/CU_TE.jpg"

export default {
  name: 'App',
  data () {
    return {
      url: url,
    }
  }
}
</script>

<style>

</style>
