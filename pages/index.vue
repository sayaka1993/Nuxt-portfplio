<template>
  <div class="container">
    <div>
       <img src="~/assets/img/img01.png">
       <h1>
       my portfolio
       </h1>
      <h2>
        presented by<br>
        sayaka irie
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
*{
padding:0;
margin:0;
}
.container {
  margin: 0;
  min-height: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

h1{
  font-family:
   serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
  margin-top:-55%;
  animation-dlay: 1s;
}


h2{
  font-family:
   serif;
  display: block;
  font-weight: 300;
  font-size: 45px;
  color: #35495e;
 margin-left: 50%;
}

.links {
  padding-top: 15px;
}

img{
box-sizing: border-box;
    margin: 40px 0 0 0;
    padding: 0;
    height: 100%;
    width: 100%;
}
</style>
