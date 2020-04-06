<template>
  <div>
    <p>{{ $t("about.title") }}</p>
    <p v-html="$t('about.content')" />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.test {
  color: tomato;
}
</style>
