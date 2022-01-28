<template>
  <section id="resume">
    <h1 class="h1">My qualifications and work experience</h1>
    <h2 class="h2"><span style="border-bottom: 3px solid red">Resume</span></h2>
    <div class="container mt-5 mb-5">
      <div class="container">
        <div class="row">
          <div class="col-sm">
            <div class="resum">
              <div class="col-md-6 offset-md-3">
                <h4>Work</h4>
                <ul class="timeline">
                  <li>
                    <h7 class="h7">Research intern @ HSRC</h7><br />

                    <p class="float-right">30 May, 2021</p>
                    <p>
                      I worked as a research assistance at Human Science
                      Research Council of South Africa.
                    </p>
                  </li>
                  <li>
                    <h7 class="h7"> Freelance cartographer</h7><br />

                    <p class="float-right">June, 2020</p>
                    <p>
                      Did some freelance work creating maps for researchers
                      within the GIS <br />field from mid-2020
                    </p>
                  </li>
                  <li>
                    <h7 class="h7">Tutor </h7><br />

                    <p class="float-right">24 February, 2019</p>
                    <p>
                      Worked as a Geographic Information Sciences tutor at the
                      University of Western Cape from 2019 to 2020.
                    </p>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-sm">
            <div class="resum">
              <div class="col-md-6 offset-md-3">
                <h4>Education</h4>
                <ul class="timeline">
                  <li>
                    <h7 class="h7">LifeChoices Academy </h7><br />

                    <p class="float-right">Sep, 2021 - present</p>
                    <p>Enrolled for a coding course at LifeCHoices Academy</p>
                  </li>
                  <li>
                    <h7 class="h7">Honours degree </h7><br />

                    <p class="float-right">Feb, 2020 - Nov, 2020</p>
                    <p>
                      Completed Honours degree in GIS and Enviroonmental
                      Management at the UNiversity of Western Cape
                    </p>
                  </li>
                  <li>
                    <h7 class="h7">Graduated for Honours </h7><br />

                    <p class="float-right">24 Feb 2017 - 20 Nov 2019</p>
                    <p>
                      Undergraduate degree in Geography and Environmental
                      Studies at the University of Western Cape
                    </p>
                  </li>
                </ul>
              </div>
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
.h7 {
  color: rgb(0, 0, 0);
  font-size: larger;
}

ul.timeline {
  list-style-type: none;
  position: relative;
}
ul.timeline:before {
  content: " ";
  background: #d4d9df;
  display: inline-block;
  position: absolute;
  left: 29px;
  width: 2px;
  height: 100%;
  z-index: 400;
}
ul.timeline > li {
  margin: 20px 0;
  padding-left: 20px;
}
ul.timeline > li:before {
  content: " ";
  background: white;
  display: inline-block;
  position: absolute;
  border-radius: 50%;
  border: 3px solid #e83922;
  left: 20px;
  width: 20px;
  height: 20px;
  z-index: 400;
}
.mb-5 {
  display: flex;
}
h4 {
  text-align: center;
}
#cont2 {
  height: 79vh;
  padding-top: 0;
}
.resum {
  display: flex;
  flex-wrap: wrap;
}

@media screen and (max-width: 600px) {
  .resum {
    display: flex;
    flex-wrap: wrap;
    padding-top: 15px;
  }
}
</style>
