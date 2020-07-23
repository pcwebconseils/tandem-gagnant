<template>
  <div class="container is-fluid">
    <div class="columns">
      <div class="column is-11">
        <nuxt />
      </div>
      <div class="column is-hidden-mobile">
        <Sidebar />
      </div>
    </div>
   <div>
      <Footer />
    </div>
</div>
</template>
<script>
import Footer from "@/components/Footer.vue";
import Sidebar from "@/components/Sidebar.vue";
export default {
  components: {
    Sidebar,
    Footer,
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
/*   box-sizing: border-box;
  margin: 0;
 */}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
.container {
  padding-left: 0;
  padding-right: 0;
  /* height: 100vh; */
}

</style>
