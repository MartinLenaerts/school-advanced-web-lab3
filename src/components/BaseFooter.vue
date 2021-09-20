<template>
  <div class="footer-container">
    <div class="footer-element">
      <a href="#">Home</a>
    </div>
    <div class="footer-collapse"></div>
    <div class="footer-element">
      <a href="#"><v-icon />User</a>
    </div>
  </div>
</template>
<script>
export default {
  name: "BaseFooter",
};
</script>
<style>
.footer-container {
  display: flex;
  background-color: rgb(91, 181, 135);
  margin: 0;
  padding: 1rem;
  bottom: 0;
  position: absolute;
  width: 100%;
}
.footer-element {
  margin: auto;
}
.footer-element > a {
  color: inherit;
  text-decoration: none;
}
</style>