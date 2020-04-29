<template>
  <header>
    <!-- Nav tabs -->
    <ul class="nav nav-tabs" id="navId">
      <nuxt-link to="/">
        <li class="nav-item">
          <a href="#" class="nav-link disabled">Home</a>
        </li></nuxt-link
      >
      <nuxt-link to="about">
        <li class="nav-item">
          <a href="#tab5Id" class="nav-link">A propos</a>
        </li></nuxt-link
      >
    </ul>

    <!-- Tab panes -->
    <div class="tab-content">
      <div class="tab-pane fade show active" id="tab1Id" role="tabpanel"></div>
      <div class="tab-pane fade" id="tab2Id" role="tabpanel"></div>
      <div class="tab-pane fade" id="tab3Id" role="tabpanel"></div>
      <div class="tab-pane fade" id="tab4Id" role="tabpanel"></div>
      <div class="tab-pane fade" id="tab5Id" role="tabpanel"></div>
    </div>
  </header>
</template>
