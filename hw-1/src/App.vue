<script setup>
const currentDate = new Date();

const day = currentDate.getDate();
const month = currentDate.getMonth() + 1;
const year = currentDate.getFullYear();
</script>

<template>
  <span>{{ (day >= 10 ? day : "0" + day) + "." + (month >= 10 ? month : "0" + month) + "." + year }}</span>
</template>

<style scoped>

</style>
