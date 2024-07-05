<script setup>
import useNumbers from "@/composables/useNumbers";
import GreatGrandChild from "./GreatGrandChild.vue";

const { numbers } = useNumbers();
</script>
<template>
  <div>
    <h1>Grand Child</h1>
    {{ numbers }}
    <div class="line"></div>
    <GreatGrandChild />
  </div>
</template>
