<template>
  <div class="header-container">
    <div class="header-element">
      <a href="#">Home</a>
    </div>
    <div class="header-collapse"></div>
    <div class="header-element">
      <a href="#"><v-icon />User</a>
    </div>
  </div>
</template>
<script>
export default {
  name: "BaseHeader",
};
</script>
<style>
.header-container {
  display: flex;
  background-color: rgb(91, 181, 135);
  margin: 0;
  padding: 1rem;
}
.header-element {
  margin: auto;
}
.header-element > a {
  color: inherit;
  text-decoration: none;
}
</style>