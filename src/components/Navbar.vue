<template>
  <div class="nav-menu">
    <router-link :to="`/${$i18n.locale}`">Home</router-link>
    <router-link :to="`/${$i18n.locale}/about`">About</router-link>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
a {
  margin: 10px;
}
</style>
