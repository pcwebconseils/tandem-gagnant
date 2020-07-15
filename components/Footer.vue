<template>
  <div class="footer">
    <nuxt-link to="/">Home</nuxt-link>
    <nuxt-link to="/about">A propos</nuxt-link>
  </div>
</template>

<style>
.footer{
  width: 100%;
  height: 5vh;
  display: flex;
  justify-content: space-around;
  background: #28AEAA;
  position: fixed;
  bottom: 0;
}
a{
  color: azure;
}
a:hover{
  color: azure;text-decoration: none;font-size: large;
}
</style>
