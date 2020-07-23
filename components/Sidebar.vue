<template>
  <div class="sidenav">
    <nuxt-link to="/"><font-awesome-icon :icon="['fas', 'home']"/></nuxt-link>
    <nuxt-link to="/about"><font-awesome-icon :icon="['fas', 'quote-left']"/></nuxt-link>
    <nuxt-link to="/partenaires"><font-awesome-icon :icon="['fas', 'people-arrows']"/></nuxt-link>
    <nuxt-link to="/services"><font-awesome-icon :icon="['fas', 'business-time']"/></nuxt-link>
    <nuxt-link to="/contact"><font-awesome-icon :icon="['fas', 'coffee']"/></nuxt-link>
</div>
</template>

<style scoped>
.sidenav {
  height: 100%;
  width: 5%;
  position: fixed;
  z-index: 1;
  top: 0;
  right: 0;
  text-transform: uppercase;
  background: #28AEAA;
  background: -webkit-gradient(linear, left top, left bottom, from(#0de7c3), color-stop(90%, #28AEAA));
  background: linear-gradient(180deg, #0de7c3 0%, #28AEAA 90%);
  overflow-x: hidden;
}

.sidenav a {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 25px;
  color: #f5f3f3;
  display: block;
/*   margin-top: 50%;
 */}

.sidenav a:hover {
  color: #f1f1f1;
}
.nuxt-link-exact-active{
  -webkit-box-shadow: 10px 10px 20px 2px rgba(0,0,0,0.75);
-moz-box-shadow: 10px 10px 20px 2px rgba(0,0,0,0.75);
box-shadow: 0px 10px 20px 1px rgba(0,0,0,0.75);
margin-bottom: 1em;
}
</style>
