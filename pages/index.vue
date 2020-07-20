<template>
     <div class="main">
    <div class="tile is-ancestor">
      <div class="tile is-parent ">
        <div class="tile is-child ">
            <figure class="logo trait">
              <img src="/logo.png" alt="">
            </figure>
        </div>
    </div>
    
    <div class="tile is-parent mt-3">
        <div class="tile is-child is-8 is-desktop-10">
          <article class="circle">
            <div class="circle-content">
              <h3 class="title has-text-white">Mes services</h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos assumenda sequi illo pariatur, sint laudantium nemo sed fugit quas dicta? Lorem ipsum dolor, sit amet consectetur adipisicing elit. Atque, provident tempore ipsum praesentium dolores dolor amet quod necessitatibus nam reprehenderit optio magnam. Quasi, nam. Cupiditate dignissimos provident sunt obcaecati laudantium. Quia, necessitatibus autem sint debitis amet fugit obcaecati voluptate?</p>
              <button>lien </button>
            </div>
          </article>
        </div>
        <div class="tile is-child">
          <article class="circle-small-contact">
            <div class="circle-content">
              <h3 class="title">Contact</h3>
              <p class="" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis a repudiandae pariatur possimus sit autem?</p>
              <button>bouton de clic</button>
            </div>
          </article>
        </div>
      </div>
    </div>
    <div class="tile is-ancestor">
      <div class="tile is-parent">
        <div class="tile is-child is-8">
          <article class="circle-about">
            <div class="circle-content">
              <h3 class="title has-text-white-ter	">Vincent</h3>
              <p class="has-text-white-ter">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Facere voluptas esse eum officia iure nobis id, sequi cum suscipit tenetur. Ea laborum alias ipsam ipsum sequi tenetur illo error molestiae.</p>
            </div>
          </article>
        </div>
        <div class="tile is-child">
          <article class="circle-small">
            <div class="circle-content">
              <h3 class="title">quatre</h3>
              <p><i class="fas fa-camera fa-stack-1x"></i>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Cupiditate qui mollitia, voluptatum rem soluta culpa eum accusantium ab nesciunt veritatis?</p>
              <button>lien </button>
            </div>
          </article>
        </div>
      </div>
      <div class="tile is-parent is-vertical">
       
        <div class="tile is-child is-6">
          <article class="circle-small-divers">
            <div class="circle-content">
              <h3 class="title has-text-black-bis">six</h3>
              <p class="has-text-black-bis">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Cupiditate qui mollitia, voluptatum rem soluta culpa eum accusantium ab nesciunt veritatis?</p>
              <button>lien</button>
            </div>
          </article>
        </div>
         <div class="tile is-child is-8">
          <article class="circle-small-outils">
            <div class="circle-content">
              <h3 class="title has-text-black-ter">cinq</h3>
              <p class="has-text-black-ter">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Cupiditate qui mollitia, voluptatum rem soluta culpa eum accusantium ab nesciunt veritatis?</p>
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
    background-color: #e78f0a;
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    overflow: hidden;
}
.circle-small-divers{
    border: #28AEAA 0.2rem solid;
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    transform: translate(-5%, -5%);
    overflow: hidden;
}
.circle-small-outils{
    border: #e78f0a 0.2rem solid;
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    transform: translate(50%, -50%);
    overflow: hidden;
}
.circle-small-contact{
    border: #28AEAA 0.1rem solid;
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    transform: translate(15%, 80%);
    overflow: hidden;
}
.circle-small{
    border: #e78f0a 0.2rem solid;
    border-radius: 50%;
    height: 0;
    padding-top: 100%;
    width: 100%;
    position: relative;
    transform: translate(-10%, 90%);
    overflow: hidden;
}
.circle-about{
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
.circle-content{
    /* padding-top: 50%; */
    height: 100%;
    width: 100%;
    margin-top: 2em;
    padding-right: 2em;
    padding-left: 2em;
    position: absolute;
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    white-space: pre-wrap;
}
.logo{
  width: 75%;
  height: auto;
  margin-left: 5%;
}
.trait::after{
  content: '';
  display: block;
  width: 150%;
  height: 0.25em;
  background-color: #28AEAA;
}

</style>>