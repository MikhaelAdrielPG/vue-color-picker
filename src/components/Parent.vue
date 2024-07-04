<script setup>
import useNumbers from "@/composables/useNumbers";
import Child from "./Child.vue";

const { numbers, addNumber } = useNumbers();
</script>
<template>
  <div>
    <h1>Parent</h1>
    {{ numbers }}
    <button @click="addNumber">Add</button>
    <div class="line"></div>
    <Child />
  </div>
</template>
