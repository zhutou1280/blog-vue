<template>
  <div>
    <header></header>
    <div class="main">
      <div class="aside">
        <nav-container></nav-container>
      </div>
      <div class="center">
        <Content></Content>
      </div>
    </div>
    <footer>
      <div class="copyright">© 2020 苏ICP备18024796号-1</div>
    </footer>
  </div>
</template>

<script>
import NavContainer from "./NavContainer.vue";
import Content from "./Content";
export default {
  name: "Home",
  components: { NavContainer, Content }
};
</script>

<style lang="scss">
header {
  width: "100%";
  height: 100px;
}

.main {
  max-width: 1220px;
  margin: 0 auto;
  border: 1px solid white;
  min-height: 800px;

  .aside {
    width: 300px;
    margin: 5px;
    float: left;
  }
  .center {
    margin-left: 300px;
  }
}

footer {
  width: 100%;
  height: 10px;
  .copyright {
    line-height: 1.6em;
    font-size: 0.85em;
    width: 20%;
    margin: 0 auto;
  }
}
</style>
