<template>
  <footer id="footer">
        <ul class="icons">
            <li><a href="#" class="icon fa-twitter"><span class="label">Twitter</span></a></li>
            <li><a href="#" class="icon fa-facebook"><span class="label">Facebook</span></a></li>
            <li><a href="#" class="icon fa-instagram"><span class="label">Instagram</span></a></li>
        </ul>
        <div class="copyright">
            &copy; Untitled. Design: <a href="https://templated.co">TEMPLATED</a>. Images: <a href="https://unsplash.com">Unsplash</a>.
        </div>
    </footer>
</template>

<script>
export default {

}
</script>

<style scoped>
.fa-twitter:hover {
    color: #00acee !important;
}
.fa-facebook:hover {
    color: #3b5998 !important;
}
.fa-instagram:hover {
  color: transparent !important;
  background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fdf497 5%, #fd5949 45%, #d6249f 60%, #285AEB 90%) !important;
  background-clip: text !important;
  -webkit-background-clip: text !important;
}
.fa-instagram:hover {
    height: 40px;
    width: 27px;
    display: inline-block;
}
#footer {
    padding: 1em 0 1em 0
}
#footer .copyright {
    margin: 0;
}
</style>