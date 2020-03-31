<template>
  <div id="app">
    <!-- Header -->
			<app-header></app-header>

		<!-- Banner -->
      <banner></banner>
		<!-- Blogs -->
			<blogs></blogs>

		<!-- Footer -->
    <app-footer></app-footer>
			
  </div>
</template>

<script>
import AppHeader from './components/Header.vue';
import Blogs from './components/Blogs.vue';
import Banner from './components/Banner.vue';
import AppFooter from './components/Footer.vue';

export default {

  name: 'App',
  components: {
    AppHeader,
    Blogs,
    Banner,
    AppFooter
  }
  
}
</script>

<style>
body {
    padding: 0em !important; 
}
</style>
