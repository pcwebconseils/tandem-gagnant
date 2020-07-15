<template>
  <div class="container is-fluid">
    <nuxt />
    <Sidebar/>
    <Footer />
  </div>
</template>
<script>
import Footer from "@/components/Footer.vue";
import Sidebar from "@/components/Sidebar.vue";
import Logo from "@/components/Logo.vue";
export default {
  components: {
    Sidebar,
    Footer,
    Logo
  }
};
</script>
<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;

}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
.container{
  background-color: darkcyan;

}
.logo{
  width: 100%;
  height: auto;
}

</style>
