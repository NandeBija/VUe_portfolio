<template>
  <section id="cont2">
    <div class="contact">
      <h1>Contact page</h1>
      <div class="container">
        <div class="row">
          <div class="col">
            <div class="left-container">
              <div class="left-inner-container">
                <h2>Let's Chat!</h2>
                <p>
                  Whether you have a question, want to start a project or simply
                  want to connect.
                </p>
                <br />
                <p>Feel free to send me a message in the contact form</p>
              </div>
              <div class="address">
                <div>
                  <i class="material-icons">email</i>
                  <p>@mail.com</p>
                </div>
                <div>
                  <i class="material-icons">map</i>
                  <p>Address</p>
                </div>
                <div>
                  <i class="material-icons">phone</i>
                  <p>+27 12 3456 789</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <form
              @submit.prevent="handleSubmit"
              role="form"
              action="https://formspree.io/f/xknyjnke"
              method="post"
            >
              <!-- the 'dot prevent' prevents the form from cleaaring the data back to default after submitting -->

              <label> Name:</label>
              <input
                type="text"
                required
                v-model="name"
                placeholder="Enter full name and surname"
              />
              <label> Email:</label>
              <input
                type="email"
                required
                v-model="email"
                placeholder="Enter your email"
              />

              <label> Number:</label>
              <input
                type="text"
                required
                v-model="number"
                placeholder="Enter your number"
              />
              <div v-if="numberError" class="number">{{ numberError }}</div>

              <!--  dropdown for the role of whoever uses the form-->
              <label> Role:</label>
              <select v-model="role">
                <option value="developer">Web developer</option>
                <option value="designer">Web designer</option>
                <option value="interested">Interested party</option>
                <option value="other">Other</option>
              </select>
              <label> Message:</label>
              <input
                type="message"
                placeholder=""
                v-model="message"
                id="message"
              />
              <!-- working with checkboxes using booleans  -->
              <div class="terms">
                <input type="checkbox" v-model="terms" required />
                <label> Accept terms and conditions</label>
              </div>
              <div class="submit">
                <button @click="submit">Submit</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      name: "", //This starts of as an empty string in order for it to be updated by what //
      //the user types in the webpage//
      number: "",
      role: "",
      terms: false,
      // names: [],
      message: "",
      numberError: "", //   erro message for when number is less than 10characters
    };
  },
  methods: {
    handleSubmit() {
      //   validate number has more than 10 characters
      this.numberError =
        this.number.length > 9
          ? ""
          : "Number must be at least 10 characters long";
    },
    submit() {},
  },
};
</script>

<style scoped>
#cont2 {
  background-color: rgb(233, 245, 219);
}
form {
  max-width: 100%;
  margin: 30px auto;
  background: rgb(185, 96, 96);
  text-align: left;
  padding: 40px;
  border-radius: 10px;
}
h2 {
  padding: 20px;
}
.address {
  display: flex;
}
.address i {
  font-size: 60px;
  padding: 65px;
}

label {
  color: rgb(12, 6, 6);
  display: inline-block;
  margin: 25px 0 15px;
  font-size: 0.6em;
  text-transform: uppercase;
  letter-spacing: 1px;
  font-weight: bold;
}
input,
select {
  display: block;
  padding: 10px 6px;
  width: 100%;
  box-sizing: border-box;
  border: none;
  border-bottom: 1px solid #ddd;
  color: #555;
}
.cont {
  color: rgb(228, 18, 18);
}
.number {
  color: yellow;
  margin-top: 10px;
  font-weight: bold;
}
form {
  height: 94%;
}
input[type="checkbox"] {
  display: inline-flex;
  width: 16px;
  margin: 0 10px 0 0;
  position: relative;
  top: 2px;
}
#message {
  height: 110px;
}
.left-inner-container {
  padding-top: 130px;
}
.contact {
  box-shadow: 20px;
}
button {
  background: white;
  border: 1px;
  float: right;
  padding-bottom: 20px;
  padding: 5px 15px;
  border-radius: 20px;
}
.submit {
  text-align: center;
}

@media screen and (max-width: 600px) {
  .address i {
    font-size: 60px;
    padding: 20px;
  }
}
</style>
