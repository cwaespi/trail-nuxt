<template>
  <main>
    <Header />
    <Navigation />
    <slot />
    <Footer />
  </main>
</template>

<style scoped>
main {
  display: grid;
  gap: 20px;
  grid-template-columns: 1fr 4fr 1fr;
  grid-template-areas:
    "header  header  header"
    "nav     nav     nav"
    "content content ad"
    "footer  footer  footer";
  background: #fff;
}
</style>
