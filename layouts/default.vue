<template>
  <div>
    <header class="title">
      <NuxtLink to="/">Nuxt Shopping</NuxtLink>
    </header>
    <Nuxt />
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
header {
  height: 60px;
  display: flex;
  align-items: center;
  padding: 0.05rem;
}
.logo {
  font-weight: 900;
}
.logo:visited {
  color: inherit;
}
</style>