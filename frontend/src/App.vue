<script setup>
import AppartementList from './components/AppartementList.vue'
import Header from './components/Header.vue'

fetch('http://localhost:5001/train-note', {
  method: 'POST',
  headers: {
    'Accept': 'application/json',
  },
  body: ''
});
fetch('http://localhost:5001/train-year', {
  method: 'POST',
  headers: {
    'Accept': 'application/json',
  },
  body: ''
});
fetch('http://localhost:5001/train-garage', {
  method: 'POST',
  headers: {
    'Accept': 'application/json',
  },
  body: ''
});
</script>

<template>
    <Header />
    <AppartementList />
</template>

<style scoped>

</style>
