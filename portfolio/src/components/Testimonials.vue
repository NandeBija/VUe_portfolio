<template>
  <section id="testimonil">
    <div class="container">
      <div class="row">
        <h1 class="h1">More about me</h1>
        <h2 class="h2">
          <span style="border-bottom: 3px solid red">Testimonials</span>
        </h2>
        <div class="col-sm-6">
          <div class="test">
            <img
              src="../assets/Godwin.jpeg"
              class="test-img-top"
              alt="Godwin's testimonial picture"
            />
            <div class="card-body">
              <h5 class="card-title">
                <span class="comma">"</span>I have no hesiotancy writing a
                recommendation for Nande. He has a bright future in the
                industry<span class="comma"> "</span>
              </h5>
              <p class="card-text">
                Godwin Dzvapatsva<span class="comma">|</span> Lecturer
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm-6">
          <div class="test">
            <img
              src="../assets/siyanda.jpeg"
              class="test-img-top"
              alt="Siyanda's testimonial picture"
            />
            <div class="card-body">
              <h5 class="card-title">
                <span class="comma">"</span>Nande is a very professional,
                hard-working individual and a talanted developer. He will be a
                success in the industry <span class="comma"> "</span>
              </h5>
              <p class="card-text">
                Siyanda Ncamazana<span class="comma">|</span> Collegue
              </p>
            </div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-sm-6">
          <div class="test">
            <img
              src="../assets/emma.jpeg"
              class="test-img-top"
              alt="Emmanuel'stestimonial picture"
            />
            <div class="card-body">
              <h5 class="card-title">
                <span class="comma">"</span> I have known Nande as a collegue
                and a friend outside the workplace for long. He is a creative
                individual and very fun to work with.<span class="comma">
                  "</span
                >
              </h5>
              <p class="card-text">
                Emanuel Fente<span class="comma">|</span> Collegue
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm-6">
          <div class="test">
            <img
              src="../assets/chad.jpg"
              class="test-img-top"
              alt="Azabenathi's testimonial picure"
            />
            <div class="card-body">
              <h5 class="card-title">
                <span class="comma">"</span> I've had the chance to know Nande
                and work with him over the past few months. He has a dedicated
                individual and has a great work ethic<span class="comma">
                  "</span
                >
              </h5>
              <p class="card-text">
                Chad Hendricks<span class="comma">|</span> Collegue
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- <hr class="seperater"> </hr> -->
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
#testimonil {
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
.test-img-top {
  width: 300px;
  height: 250px;
  border-radius: 8%;
  padding: 10px;
  padding-left: 3%;
  align-items: center;
}
.test {
  text-align: center;
  justify-items: start;
}
.comma {
  color: red;
  font-size: 25px;
}
</style>
