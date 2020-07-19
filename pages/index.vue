<template>
     <div class="main">
    <div class="tile is-ancestor">
      <div class="tile is-parent is-vertical">
        <div class="tile is-child">
            <figure class="mt-6 ml-6">
              <img src="/logo.png" alt="">
            </figure>
        </div>
        <div class="tile is-child trait">
      </div>
    </div>
    
    <div class="tile is-parent">
        <div class="tile is-child is-8">
          <article class="circle-full">
            <div class="circle-content mt-6">
              <h2 class="title">Contact</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos assumenda sequi illo pariatur, sint laudantium nemo sed fugit quas dicta?<br>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Atque, provident tempore ipsum praesentium dolores dolor amet quod necessitatibus nam reprehenderit optio magnam. Quasi, nam. Cupiditate dignissimos provident sunt obcaecati laudantium. Quia, necessitatibus autem sint debitis amet fugit obcaecati voluptate?</p>
            </div>
          </article>
        </div>
        <div class="tile is-child">
          <article class="circle-bas">
            <div class="circle-content">
              <h2 class="title">Contact</h2>
              <button>bouton de clic</button>
            </div>
          </article>
        </div>
      </div>
    </a>
    </div>
    <div class="tile is-ancestor">
      <div class="tile is-parent">
        <div class="tile is-child is-6">
          <article class="circle-service-1">
            <div class="circle-content">
              <h2 class="title">Vertical tiles</h2>
              <p>Top box</p>
            </div>
          </article>
        </div>
        <div class="tile is-child is-3">
          <article class="circle-full-1  ">
            <div class="circle-content">
              <h2 class="title">Vertical tiles</h2>
              <p>Top box</p>
            </div>
          </article>
        </div>
      </div>
      <div class="tile is-parent">
        <div class="tile is-child">
          <article class="circle-service">
            <div class="circle-content">
              <h2 class="title">Vertical tiles</h2>
              <p>Top box</p>
            </div>
          </article>
        </div>
        <div class="tile is-child">
          <article class="circle-full">
            <div class="circle-content">
              <h2 class="title">Vertical tiles</h2>
              <p>Top box</p>
            </div>
          </article>
        </div>
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
<style>
/* No CSS *//*# sourceMappingURL=main.css.map */
main{
    height: 100vh;
}
.circle{
    border: gold 0.2rem solid;
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    transform: translate(0, 0);
    overflow: hidden;
}
.circle-full{
    background-color: rgb(231, 150, 0);
    border: 2px solid rgb(214, 15, 64);
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    transform: translate(-10%, 10%);
    overflow: hidden;
}
.circle-full-1{
    background-color: rgb(231, 150, 0);
    border: 2px solid rgb(214, 15, 64);
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    overflow: hidden;
    transform: translate(0, 20em);
}
.circle-service{
    border: rgb(40, 18, 236) 0.2rem solid;
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    overflow: hidden;
    transform: translate(5em, 0);
}
.circle-service-1{
    border: 2px solid rgb(214, 15, 64);
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    overflow: hidden;
    transform: translate(5em, 0);
}
.circle-content{
    /* padding-top: 50%; */
    height: 100%;
    position: absolute;
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
}
.circle-bas{
    border: rgb(11, 216, 52) 0.2rem solid;
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    /* transform: translate(50%, 250%); */
}
img{
    width: 50%;
    height: auto;
}
.trait{
    border-bottom: rgb(0, 255, 179) 0.15rem solid;
    /* transform: translateY(-12em); */
}
@media screen and (max-width: 374px){
    .circle{
        border: rgb(0, 255, 64) 0.2rem solid;
        border-radius: 50%;
        height: 0;
        padding-top: 75%;
        width: 75%;
        margin: auto;
    }
}
</style>>