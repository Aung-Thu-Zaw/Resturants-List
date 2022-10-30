<template>
  <div>
    <div class="container text-center mt-5">
      <NuxtLayout name="error">
        <template #header>
          <h1>Page Not Found</h1>
        </template>

        <template #redirectEl>
          <NuxtLink to="/" class="btn btn-primary btn-lg">Go Back</NuxtLink>
        </template>
      </NuxtLayout>
    </div>
  </div>
</template>  

<style >
</style>