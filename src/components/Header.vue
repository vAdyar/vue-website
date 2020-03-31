<template>
  <b-navbar toggleable type="dark" variant="dark">
    <img id="logo" src="../assets/logo.png" height="50px">
    <b-navbar-brand href="#">Capture moments</b-navbar-brand>
    

    <b-navbar-toggle target="navbar-toggle-collapse">
      <template v-slot:default="{ expanded }">
        <b-icon v-if="expanded" icon="chevron-bar-up"></b-icon>
        <b-icon v-else icon="chevron-bar-down"></b-icon>
      </template>
    </b-navbar-toggle>

    <b-collapse id="navbar-toggle-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#">Home</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>


<style>
#logo {
    margin: 2px 10px;
}
 .ml-auto {
    float: right;
}
.navbar-dark .navbar-toggler {
    float: right;
}
.bg-dark {
    display: flow-root !important;
}
.navbar-dark .navbar-toggler:hover {
    background-color: #ff7700
}
</style>
