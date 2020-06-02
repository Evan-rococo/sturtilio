<template>

  <div class="layout">
    <header>
<div class="navbar">
  <g-link class="logo" to="/">Hot request</g-link>
  <g-link to="/product/"><h2>search</h2></g-link>
  <g-link to="/product/"><h2>cart</h2></g-link>
</div>

    </header>
      <div class="sidenav">
  <g-link to="/genre/">new stuff</g-link>
  <g-link to="/genre/">afro</g-link>
  <g-link to="/genre/">boogie</g-link>
  <g-link to="/genre/">esoteric</g-link>
  <g-link to="/genre/">pop music</g-link>
  <g-link to="/genre/">reggae</g-link>
  <g-link to="/genre/">tropical</g-link>
      <div class="sidenav">
        <g-link to="/genre/">contact</g-link>
        <g-link to="/genre/">blog</g-link>
        <g-link to="/genre/">instagram</g-link></div>
        </div>
    
    <slot/>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>





<style>
body {
  font-family: "Elmo";
  margin:0;
  padding-right:3vw;
  line-height: 1.;
  width: 100%;
}

.h1 {
  font-family: "medi";
  font-size:  2.5em;
}

.p {
  font-family: "elmo";
  font-size: 1.5vw;
}

h2 {
  font-family: "elmo";
  font-size: 1.5em;
  margin-top: 0.3em;
  margin-bottom: 0.3em;
}

h3 {
  font-family: "elmo";
  text-align: right;
  font-size: 1.5em;
  margin-top: 0.3em;
  margin-bottom: 0.3em;
}

.logo {
  font-family: "medi";
  font-size:  2.66em;
  letter-spacing: -0.05em;
  color: black;
  }

.layout {
  max-width: 100%;
  margin-right: 0em;
  padding-left: 0px;
  padding-right: 9vw;
  }

.nav__link {
  margin-left: 0px;
  text-decoration: none;
  color: black;
}



@font-face {
    font-family: 'Elmo';
    src: url('../static/elmer-webfont.woff') format('woff'), /* Modern Browsers */
         url('../static/elmer-webfont.ttf') format('truetype'); /* Safari, Android, iOS */
             font-style: normal;
    font-weight: normal;
    text-rendering: optimizeLegibility;}
@font-face {
    font-family: 'medi';
    src: url('../static/GintoNordTrial-Medium.woff') format('woff'), /* Modern Browsers */
         url('../static/GintoNordTrial-Medium.ttf') format('truetype'); /* Safari, Android, iOS */
             font-style: normal;
    font-weight: normal;
    text-rendering: optimizeLegibility;}

* {box-sizing: border-box;}

.navbar {
  overflow: hidden;
  position: fixed; 
  margin-top: 1em; /* Position the navbar at the top of the page */
  margin-left:2vw;
  width: 100%; /* Full width */
}

.navbar a {
  float: left;
  display: block;
  text-align: center;
  margin-right: 2vw;
  text-decoration: none;
  color: black;
}

/* Change background on mouse-over */
.navbar a:hover {
  color: red;
}

/* Main content */
.main {
  margin-top: 0px; /* Add a top margin to avoid content overlay */
}

.sidenav {
  width: 9em;
  position: fixed;
  z-index: 1;
  background:chartreuse;
  

  overflow-x: hidden;
  color: black;
  margin-left: 2vw;
  margin-top: 5em;
  
}

.sidenav a {
  text-decoration: none;
  font-size: 1.5em;
  color: black;
  display: block;
  margin-top: 0.1em;
  margin-bottom: 0.1em;
}

.sidenav a:hover {
  color: red;
}

.main {
  font-size: 2em;
}
.topnav input[type=text] {
  float: right;
  padding: 6px;
  border: none;
  margin-top: 8px;
  margin-right: 16px;
}


@media screen and (max-width: 600px) {
  .topnav a, .topnav input[type=text] {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
  .topnav input[type=text] {
  }
}

</style>
