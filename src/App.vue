<template>
  <v-container fluid pl-0 pr-0 pt-0 pb-0>
    <v-layout align-center justify-center class="container">
      <v-flex xs12 class="box">
        hello world!
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data () {
    return {
      //
    }
  }
}
</script>
<style lang="stylus" scoped>
.container
  width 100%
  height calc(100vh)
  background-color aqua
  .box
    text-align center
</style>
