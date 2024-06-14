<script setup lang="ts">
import { AProps } from "./types";
import A from "./A.vue";

const props = defineProps<AProps>();
</script>

<template>
  <A v-bind="$props"></A>
</template>
