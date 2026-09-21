<script setup>
import { useI18n } from "vue-i18n";

const { t } = useI18n();
</script>

<template>
  <section class="mt-6 p-4 md:p-5">
    <div class="max-w-lg mx-auto gap-3">
      <h1 class="text-4xl font-bold text-color">{{ t('about.title') }}</h1>
      <p class="text-lg font-light text-color-secondary">{{ t('about.content') }}</p>
    </div>
  </section>
</template>

<style scoped>

</style>
