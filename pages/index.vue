<template>
    <div class="tile is-ancestor">
      <div class="tile is-4 is-parent">
        <div class="tile is-child box logo">
          <Logo />
        </div>
        <div class="tile is-child box">
          <p class="title">Two</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ornare magna eros, eu pellentesque tortor vestibulum ut. Maecenas non massa sem. Etiam finibus odio quis feugiat facilisis.</p>
        </div>
        <div class="tile is-child box">
          <p class="title">Three</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam semper diam at erat pulvinar, at pulvinar felis blandit. Vestibulum volutpat tellus diam, consequat gravida libero rhoncus ut. Morbi maximus, leo sit amet vehicula eleifend, nunc dui porta orci, quis semper odio felis ut quam.</p>
        </div>
      </div>
      <div class="tile is-4 is-parent">
        
        <div class="tile is-child box home-items">
          <p class="title">Four</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam semper diam at erat pulvinar, at pulvinar felis blandit. Vestibulum volutpat tellus diam, consequat gravida libero rhoncus ut. Morbi maximus, leo sit amet vehicula eleifend, nunc dui porta orci, quis semper odio felis ut quam.</p>
        </div>
      </div>
      <div class="tile is-4 is-parent">
        <div class="tile is-child home-items box">
          <p class="title">Four</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam semper diam at erat pulvinar, at pulvinar felis blandit. Vestibulum volutpat tellus diam, consequat gravida libero rhoncus ut. Morbi maximus, leo sit amet vehicula eleifend, nunc dui porta orci, quis semper odio felis ut quam.</p>
        </div>
        <div class="tile is-child box home-items">
          <p class="title">Four</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam semper diam at erat pulvinar, at pulvinar felis blandit. Vestibulum volutpat tellus diam, consequat gravida libero rhoncus ut. Morbi maximus, leo sit amet vehicula eleifend, nunc dui porta orci, quis semper odio felis ut quam.</p>
        </div>
      </div>
    </div>
</template>
<script>
import Logo from "@/components/Logo.vue";
export default {
  components: {
    Logo
  }
};
</script>
<style lang="css" scoped>
.tile, .is-4, .is-vertical, .is-parent{
  /* height: 100vh; */
  /* padding-top: 1%; */
  /* margin-top: 1rem; */
}
</style>>