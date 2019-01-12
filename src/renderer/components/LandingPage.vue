<template>
  <div class="container-fluid">
    <div class="card">
      <div class="card-body">
        This is some text within a card body.
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'landing-page',
  components: {},
  methods: {
    open (link) {
      this.$electron.shell.openExternal(link)
    }
  }
}
</script>

<style>
  /* CSS */
</style>
