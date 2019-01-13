<template>
  <div class="container-fluid">
    <div class="card my-3">
      <div class="card-body">
        <h3><i class="fas fa-cog text-primary"></i> Settings</h3>
      </div>
    </div>
    <nav>
      <ol class="breadcrumb">
        <li class="breadcrumb-item"><router-link to="/">Home</router-link></li>
        <li class="breadcrumb-item active">Settings</li>
      </ol>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'settings-page',
  components: {}
}
</script>

<style>
/* CSS */
</style>
