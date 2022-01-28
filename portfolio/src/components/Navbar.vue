<template>
  <div class="topnav" id="myTopnav">
    <a href="#home" class="active"
      >Home <i class="fa fa-home" aria-hidden="true"></i
    ></a>
    <a href="#About">About <i class="fa fa-user"></i></a>
    <a href="#resume">Resume <i class="fa fa-briefcase"></i></a>
    <a href="#projects">Projects <i class="fa fa-cogs"></i></a>
    <a href="#testimonil">Testimonials <i class="fa fa-commenting-o"></i></a>
    <a href="#cont2">Contact <i class="fa fa-envelope"></i></a>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.topnav {
  overflow: hidden;
  background-color: #000000;
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
  z-index: 600;
}

.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  font-family: courier new;
  font-weight: bold;
}

.topnav a:hover {
  color: #ff5959;
}

.topnav a.active {
  background-color: #ff0000;
  color: white;
}

.topnav .icon {
  display: none;
}
.fa {
  position: relative;
  font-size: 22px;
  text-align: center;
  padding-left: 2px;
  color: #423d3d;
  padding-top: 5px;
}

/* MEDIA QUERIES */

@media screen and (max-width: 600px) {
  .topnav.responsive .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav a:not(:first-child) {
    display: none;
  }
  .topnav a.icon {
    float: right;
    display: block;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
  .topnav {
    overflow: hidden;
    background-color: #000000;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 600;
  }
}
</style>
