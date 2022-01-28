<template>
  <section id="projects">
    <div class="container" id="Projects">
      <div class="pro">
        <h1 class="h1">Some of my latest work</h1>
        <h2 class="h2">
          <span style="border-bottom: 3px solid red">Projects</span>
        </h2>
      </div>
      <div class="row">
        <div class="col-sm-4">
          <div class="card mb-3 shadow-lg">
            <div class="card-body">
              <h5 class="card-title">Timeline Project</h5>
              <img
                src="../assets/time.png"
                class="card-img-top"
                alt="Timeline project"
              />
              <span class="hov"
                ><a
                  href="https://github.com/NandeBija/timeline.git"
                  class="fa fa-github"
                ></a
              ></span>
            </div>
          </div>
        </div>
        <div class="col-sm-4">
          <div class="card mb-3 shadow-lg">
            <div class="card-body">
              <h5 class="card-title">Speed reactor game</h5>
              <br />
              <img
                src="../assets/reactor.png"
                class="card-img-top"
                alt="ecommerce"
              />
              <span class="hov"
                ><a
                  href="https://github.com/NandeBija/ReactionTImer_game.git"
                  class="fa fa-github"
                ></a
              ></span>
            </div>
          </div>
        </div>
        <div class="col-sm-4">
          <div class="card mb-3 shadow-lg">
            <div class="card-body">
              <h5 class="card-title">Cards project</h5>
              <img
                src="../assets/cards2.png"
                class="card-img-top"
                alt="Cards project"
              />
              <span class="hov"
                ><a
                  href="https://github.com/NandeBija/Cards.git"
                  class="fa fa-github"
                ></a
              ></span>
            </div>
          </div>
        </div>
        <div class="col-sm-4">
          <div class="card mb-3 shadow-lg">
            <div class="card-body">
              <h5 class="card-title">BMI calculator</h5>
              <img
                src="../assets/BMI.png"
                class="card-img-top"
                alt="BMI calc"
              />
              <span class="hov"
                ><a
                  href="https://github.com/NandeBija/BMI.git"
                  class="fa fa-github"
                ></a
              ></span>
            </div>
          </div>
        </div>
        <div class="col-sm-4">
          <div class="card mb-3 shadow-lg">
            <div class="card-body">
              <h5 class="card-title">Maths calculator</h5>
              <img
                src="../assets/calculator.png"
                class="card-img-top"
                alt="calculator"
              />
              <span class="hov"
                ><a
                  href="https://github.com/NandeBija/calculator.git"
                  class="fa fa-github"
                ></a
              ></span>
            </div>
          </div>
        </div>
        <div class="col-sm-4">
          <div class="card mb-3 shadow-lg">
            <div class="card-body">
              <h5 class="card-title">eComerce store</h5>
              <img
                src="../assets/ecommerce.png"
                class="card-img-top"
                alt="ecommerce"
              />
              <span class="hov"
                ><a
                  href="https://github.com/NandeBija/Glasses-ecommerce.git"
                  class="fa fa-github"
                ></a
              ></span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
#projects {
  background-color: rgb(233, 245, 219);
  height: 100vh;
}
.h2,
h2 {
  text-align: center;
  padding-bottom: 8px;
}
.h1,
h1 {
  text-align: center;
  color: gray;
  font-size: medium;
  padding-top: 1.5%;
}
.pro {
  padding-bottom: 4%;
}
.card-body img {
  height: 20%;
  border-radius: 3%;
}

.card {
  column-gap: 40px;
}
.card:hover {
  transition: transform 0.5s ease-in-out;
  transform: scale(1.1);
}

@media screen and (max-width: 600px) {
  .card {
    height: 200px;
  }
  .card img {
    height: 110px;
  }
}
</style>
