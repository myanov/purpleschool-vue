<script setup>
  let getCurrentDate = () => {
    let date = new Date();
    let day = date.getDate();
    day = day < 10 ? "0" + day : day;
    let month = date.getMonth() + 1;
    month = month < 10 ? "0" + month : month;
    const year = date.getFullYear();
    return `${day}.${month}.${year}`;
  };
</script>

<template>{{ getCurrentDate() }}</template>

<style scoped></style>
