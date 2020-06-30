<template>
  <div class="container">
    <h1>Hello.</h1>
    <p style="font-weight:500; font-size:2.2em">
      My name is Ren mengkai
    </p>
    <p style="margin-top:2vh;">
      I am a "brick worker" (Programmer) in second tier cities, my personal hobbies are network security and business finance.
      My current position is a Java Web Development Engineer, and I like to study small open source projects on <a href="https://github.com/renmengkai" target="_blank">GitHub</a>.
    </p>
    <p style="margin-top:2vh;">
      I am also trying to keep writing <a href="http://blog.mengkai.ren" target="_blank">Blog</a>, constantly accumulate practical and theoretical knowledge, and improve my personal ability.
    </p>
    <p style="margin-top:2vh;">
      Glad to meet you, my friend!
    </p>
    <p style="margin-top:2vh;">
      If you want to contact me, please email me. 
      <a href="mailto:renmengkai@yahoo.com" target="_blank">renmengkai@yahoo.com</a>
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style>
.container {
  font-family: "Rubik", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  font-size: calc(10px + 0.33vw);
  -webkit-font-smoothing: antialiased;
  padding: 5vh 10vw;
  color: #121314;
  margin-top: 8vh;
}
h1 {
  font-size: 4.5em;
  font-weight: 500;
  margin-bottom: 0;
}
p {
  font-size: 1.6em;
  font-weight: 300;
  line-height: 1.4;
  max-width: 32em;
}
a {
  text-decoration: none;
  color: #121314;
  position: relative;
}
a:after {
  content: "";
  position: absolute;
  z-index: -1;
  top: 60%;
  left: -0.1em;
  right: -0.1em;
  bottom: 0;
  transition: top 200ms cubic-bezier(0, 0.8, 0.13, 1);
  background-color: rgba(79, 192, 141, 0.5);
}
a:hover:after {
  top: 0%;
}
</style>
