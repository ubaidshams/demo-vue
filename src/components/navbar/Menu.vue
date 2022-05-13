<template>
  <div class="menuBlock">
    <a href=""> download app </a>
    <a href="">list property</a>
    <a href="">saved</a>
    <a href="">news</a>
  </div>
</template>
<script>
export default {
  name: "MenuBlock",
};
</script>
<style>
.menuBlock {
  width: 40%;
  display: flex;
  justify-content: space-evenly;
  align-content: center;
}
.menuBlock a {
  text-decoration: none;
  color: #111;
  text-transform: capitalize;
}
</style>
