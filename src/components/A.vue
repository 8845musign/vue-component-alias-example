<script setup lang="ts">
import { AProps } from "./types";

const props = defineProps<AProps>();
</script>

<template>
  <div>{{ props.a }}</div>
  <div>{{ props.b }}</div>
  <div>{{ props.c }}</div>
</template>
