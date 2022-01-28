<template>
 
  <section>
    <div id="home">
      <div class="box">
        <h1>
          <span class="helloText"><strong>Hello,</strong><br /></span>
          <strong class="myName">I'm Nande Bija</strong><br />
        </h1>
        <br />
        <p class="headerContent">
          Front-end developer | Back-end developer|<br /><span class="social">
            <a href="" target="_blank" class="fa fa-linkedin"></a>
            <a
              href="https://github.com"
              target="_blank"
              class="fa fa-github"
            ></a>
            <a
              href="https://github.com"
              target="_blank"
              class="fa fa-instagram"
            ></a>
          </span>
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
body {
  margin: 0px;
}
#home {
  height: 100vh;
  background-image: url("https://ucarecdn.com/118482c6-5bbc-4de5-ade2-63c59873006f/image.png");
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
}
.box {
  text-align: center;
  padding-top: 15%;
}
.helloText {
  font-size: 3.5em;
  color: #f5f5f5;
  text-align: center;
}
.myName {
  font-size: 3.7em;
  color: #ff0000b8;
  padding-top: 0%;
  font-weight: 900;
  font-family: "proxima nova bold", "Helvetica Neue", Helvetica, Arial,
    Sans-serif;
}
.headerContent {
  font-size: 2.5em;
  color: #ece8e8ef;
}
@media screen and (max-width: 600px) {
  #home {
    height: 80vh;
  }
  .box {
    text-align: center;
    padding-top: 46%;
  }
  .hellotext {
    padding-right: 68px;
  }
  .myName {
    font-size: 2.8em;
    color: #ff0000b8;
    padding-top: 0%;
    padding-right: 9%;
  }
  .headerContent {
    font-size: 2.5em;
    color: #ece8e8ef;
    padding-right: 9%;
  }
}
</style>
