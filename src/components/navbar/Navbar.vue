<template>
  <section id="navbar">
    <article>
      <Logo />
      <Menu />
    </article>
  </section>
</template>

<script>
import Logo from "./Logo.vue";
import Menu from "./Menu.vue";
export default {
  components: { Logo, Menu },
  name: "NavbarBlock",
};
</script>
<style>
#navbar {
  width: 100%;
  height: 7vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgba(0, 0, 0, 0.537);
  backdrop-filter: blur(2px);
}
#navbar article {
  width: 98%;
  height: 7vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>
