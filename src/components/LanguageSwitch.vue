<template>
  <div>
    <div class="locale-changer">
      <select v-model="$i18n.locale">
        <option v-for="(lang, i) in langs" :key="`Lang${i}`" :value="lang">{{
          lang
        }}</option>
      </select>
    </div>

    <!-- <div>
        //just test for dropdown switch language
      <a @click.prevent="setLocale('en')"></a>
      // image dynamic
       <img :src="`/flag_${$i18n.locale}.svg`" alt="flag" >
    </div> -->
  </div>
</template>

<script>
export default {
  name: "Language-switch",
  data() {
    return { langs: ["en", "fr"] };
  },
  //   methods: {
  //        this is for dropdown language switcher
  //     setLocale(locale) {
  //       this.$i18n.locale = locale;
  //       this.$router.push({
  //         params: { lang: locale },
  //       });
  //     },
  //   },
};
</script>

<style scoped></style>
