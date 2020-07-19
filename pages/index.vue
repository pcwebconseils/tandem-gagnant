<template>
     <div class="main">
    <div class="tile is-ancestor">
      <div class="tile is-parent">
        <div class="tile is-child">
            <figure>
              <img src="/logo.png" alt="">
            </figure>
        </div>
    </div>
    
    <div class="tile is-parent">
        <div class="tile is-child is-8">
          <article class="circle">
            <div class="circle-content">
              <h3 class="title">Mes services</h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos assumenda sequi illo pariatur, sint laudantium nemo sed fugit quas dicta? Lorem ipsum dolor, sit amet consectetur adipisicing elit. Atque, provident tempore ipsum praesentium dolores dolor amet quod necessitatibus nam reprehenderit optio magnam. Quasi, nam. Cupiditate dignissimos provident sunt obcaecati laudantium. Quia, necessitatibus autem sint debitis amet fugit obcaecati voluptate?</p>
              <button>lien </button>
            </div>
          </article>
        </div>
        <div class="tile is-child">
          <article class="circle">
            <div class="circle-content">
              <h3 class="title">Contact</h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis a repudiandae pariatur possimus sit autem?</p>
              <button>bouton de clic</button>
            </div>
          </article>
        </div>
      </div>
    </a>
    </div>
    <div class="tile is-ancestor">
      <div class="tile is-parent">
        <div class="tile is-child is-8">
          <article class="circle">
            <div class="circle-content">
              <h3 class="title">Vincent</h3>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Facere voluptas esse eum officia iure nobis id, sequi cum suscipit tenetur. Ea laborum alias ipsam ipsum sequi tenetur illo error molestiae.</p>
              <button>lien </button>
            </div>
          </article>
        </div>
        <div class="tile is-child">
          <article class="circle">
            <div class="circle-content">
              <h3 class="title">quatre</h3>
              <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Cupiditate qui mollitia, voluptatum rem soluta culpa eum accusantium ab nesciunt veritatis?</p>
              <button>lien </button>
            </div>
          </article>
        </div>
      </div>
      <div class="tile is-parent">
        <div class="tile is-child is-10">
          <article class="circle">
            <div class="circle-content">
              <h3 class="title">cinq</h3>
              <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Cupiditate qui mollitia, voluptatum rem soluta culpa eum accusantium ab nesciunt veritatis?</p>
              <button>lien </button>
            </div>
          </article>
        </div>
        <div class="tile is-child">
          <article class="circle">
            <div class="circle-content">
              <h3 class="title">six</h3>
              <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Cupiditate qui mollitia, voluptatum rem soluta culpa eum accusantium ab nesciunt veritatis?</p>
              <button>lien </button>
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
    /* transform: translate(0, 0); */
    overflow: hidden;
}
.circle-full{
    background-color: rgb(231, 150, 0);
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    /* transform: translate(-10%, 10%); */
    overflow: hidden;
}
.circle-full{
    background-color: rgb(231, 150, 0);
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    overflow: hidden;
    /* transform: translate(0,0); */
}
.circle{
    border: rgb(40, 18, 236) 0.2rem solid;
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    overflow: hidden;
    /* transform: translate(5em, 0); */
}
.circle{
    border: 2px solid rgb(214, 15, 64);
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    overflow: hidden;
    /* transform: translate(5em, 0); */
}
.circle{
    border: rgb(11, 216, 52) 0.2rem solid;
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    /* transform: translate(50%, 250%); */
}
.circle-content{
    /* padding-top: 50%; */
    height: 100%;
    width: 100%;
    position: absolute;
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    white-space: pre-wrap;
}
.circle-content p{
  margin: 1rem;
}
.trait{
    border-bottom: rgb(0, 255, 179) 0.15rem solid;
    /* transform: translateY(-12em); */
}
@media screen and (max-width: 375px){
    .circle{
        border: rgb(0, 255, 149) 0.2rem solid;
        border-radius: 50%;
        height: 0;
        padding-top: 75%;
        width: 75%;
        margin: auto;
    }
}
</style>>