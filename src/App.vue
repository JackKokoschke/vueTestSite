<script setup>
const message = "Vue";
const name = "bbbbb";
const year = "2025";
</script>

<template>
  <main>
    <h1>Hello {{ message }}</h1>
  </main>
  <footer>
    <p>&copy; {{ name }} {{ year }}</p>
  </footer>
</template>

<style scoped>
template {
  border: blue dashed;
}
main {
  border: red dotted;
}
h1 {
  font-weight: bold;
  text-align: center;
  color: white;
}
footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  text-align: center;
}
</style>
