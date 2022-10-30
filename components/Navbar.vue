<template>
  <nav class="navbar navbar-expand-sm navbar-dark bg-dark px-5 py-3">
    <NuxtLink to="/" class="navbar-brand">Resturtantly</NuxtLink>

    <div class="collapse navbar-collapse" id="collapsibleNavId">
      <ul class="navbar-nav ml-auto mt-2 mt-lg-0">
        <li class="nav-item">
          <NuxtLink to="/" class="nav-link">Home</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink to="/restaurants" class="nav-link">Restaurants</NuxtLink>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
</script>

<style scoped>
.ml-auto {
  margin-left: auto;
}
</style>