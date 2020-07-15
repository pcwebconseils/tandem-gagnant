<template>
  <div>
    <main>
      <nuxt />
    </main>
    <Footer />
    <Sidebar />
  </div>
</template>
<script>

import Footer from  '@/components/Footer.vue'
import Sidebar from '@/components/Sidebar.vue'
import Logo from '@/components/Logo.vue'
export default {
  components:{
    Sidebar,
    Footer,
    Logo,
  }
}
</script>
<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
main{
  display: flex;
  width: 50%;
  height: 25vh;
  margin: auto;
  justify-content: center;
  align-items: center;
  border-bottom: 2px solid orange;
}

</style>
