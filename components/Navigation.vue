<template>
  <nav>
    <NuxtLink to="/about">About</NuxtLink><a> | </a><NuxtLink to="/users-admin/123">User</NuxtLink>
  </nav>
</template>

<style scoped>
nav {
  grid-area: nav;

  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
