<template>
  <div class="container-fluid">
    <div class="card my-3">
      <div class="card-body">
        <h3><i class="far fa-bookmark text-warning"></i> Comic Manager</h3>
      </div>
    </div>
    <nav class="mb-3">
      <ol class="breadcrumb">
        <li class="breadcrumb-item active">Home</li>
      </ol>
    </nav>
    <p><router-link to="/settings"><i class="fas fa-cog text-primary"></i> Settings</router-link></p>
  </div>
</template>

<script>
export default {
  name: 'landing-page',
  components: {}
}
</script>

<style>
/* CSS */
</style>
