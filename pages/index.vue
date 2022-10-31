<template>
  <div>
    <Html :lang="dynamic > 50 ? 'en-GB' : 'en-US'">
      <Head>
        <Title>Restaurantly</Title>
        <Meta name="description" content="My page is cool" />
        <Link
          rel="preload"
          href="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png"
          as="script"
        />
      </Head>
    </Html>
    <NuxtLayout name="custom">
      <div class="container text-center mt-5">
        <h1>Welcome To Restaurantly</h1>
        <NuxtLink to="/restaurants">Go To Restaurants</NuxtLink>
      </div>
    </NuxtLayout>
  </div>
</template>  

