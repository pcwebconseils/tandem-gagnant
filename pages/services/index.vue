<template>
  <div class="tile is-ancestor">
    <div class="tile is-vertical is-8">
      <div class="tile">
        <div class="tile is-parent is-vertical">
          <article class="tile is-child notification">
            <p class="title">{{ title }}</p>
            <p class="subtitle">{{ services1 }}</p>
          </article>
          <article class="tile is-child notification">
            <p class="title">{{ title }}</p>
            <p class="subtitle">{{ subtitle }}</p>
          </article>
        </div>
        <div class="tile is-parent">
          <article class="tile is-child notification">
            <p class="title">Middle tile</p>
            <p class="subtitle">With an image</p>
            <figure class="image is-4by3">
              <img src="@/static/logo.png" />
            </figure>
          </article>
        </div>
      </div>
      <div class="tile is-parent">
        <article class="tile is-child">
          <p class="title">Wide tile</p>
          <p class="subtitle">Aligned with the right tile</p>
          <div class="content">
            <!-- Content -->
          </div>
        </article>
      </div>
    </div>
    <div class="tile is-parent">
      <article class="tile is-child notification">
        <div class="content">
          <p class="title">Tall tile</p>
          <p class="subtitle">With even more content</p>
          <div class="content">
            <!-- Content -->
          </div>
        </div>
      </article>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      title: "hello world",
      subtitle: "welecome sur le titre h2 chapeau pour le référencement",
      services1: "description du service 1",
      image: "@/static/logo.png"
    };
  }
};
</script>
<style scoped>
.content {
  background-color: #0a9994;
  /* border: rgb(0, 255, 157) 0.2rem solid; */
  border-radius: 50%;
  height: 0;
  padding-top: 100%;
  width: 100%;
  position: relative;
  /* transform: translate(-150% 0); */
  overflow: hidden;
}
</style>
