<script setup>
const month = [
  "January",
  "February",
  "March",
  "April",
  "May",
  "June",
  "July",
  "August",
  "September",
  "October",
  "November",
  "December",
];

const d = new Date();
let name = month[d.getMonth()];
</script>

<template>
  <h1>Seasonal Fruits and Vegetables</h1>
  <h2>{{ name }}</h2>
</template>

<style scoped></style>
