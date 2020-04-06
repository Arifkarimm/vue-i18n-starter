<template>
  <div>
    <div class="locale-changer">
      <select v-model="$i18n.locale">
        <option v-for="(lang, i) in langs" :key="`Lang${i}`" :value="lang">{{
          lang
        }}</option>
      </select>
    </div>
  </div>
</template>

<script>
export default {
  name: "Language-switch",
  data() {
    return { langs: ["en", "fr"] };
  },
};
</script>

<style scoped></style>
