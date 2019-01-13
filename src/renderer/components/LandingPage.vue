<template>
  <div class="container-fluid">
    <div class="card my-3">
      <div class="card-body">
        <h3><i class="far fa-bookmark text-warning"></i> Comic Manager</h3>
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
