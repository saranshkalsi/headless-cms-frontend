<template>
  <header>
    <img class="logo" src="../assets/logo.png"/>
    <h1>Review Portal</h1>

  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
header {
  background-color: #333;
  color: white;
  padding: 1rem;
  text-align: center;
  max-height: 4.50rem;
  display: flex;
  align-items: center;
  justify-content: center;
}
.logo{
  max-width: 3.125rem;
  margin-right: 0.625rem;
}
</style>
