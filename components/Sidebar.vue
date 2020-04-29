<template>
  <div class="sidenav">
  <a href="#">About</a>
  <a href="#">Services</a>
  <a href="#">Clients</a>
  <a href="#">Contact</a>
</div>
</template>
<style>
.sidenav {
  height: 100%;
  width: 160px;
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
  color: #818181;
  display: block;
  margin-top: 50%;
}

.sidenav a:hover {
  color: #f1f1f1;
}

</style>
