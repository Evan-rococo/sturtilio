<template>

  <div class="layout" style= "margin-top:1.25em; margin-left:1.25em; margin-right:1.25em; width: 100%;">
    <header>
<div class="navbar">
  <g-link class="logo" to="/">Hot request</g-link>
  <g-link to="/product/">instagram</g-link>
  <g-link to="/product/">blog</g-link>
  <div class="wrap">
   <div class="search" style="float: none;">
      <input type="text" class="searchTerm" placeholder="search">
      <button type="submit" class="searchButton">
        <i class="fa fa-search"></i>
     </button></div>
   </div>
</div>

    </header>
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
  padding:0;
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

.h2 {
  font-family: "elmo";
  font-size: 2.5vw;
}

.logo {
  font-family: "medi";
  font-size:  2em;
  letter-spacing: -0.045em; 
  }

.layout {
  max-width: 1080px;
  margin-right: 0em;
  padding-left: 20px;
  padding-right: 20px;
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
  position: fixed; /* Set the navbar to fixed position */
  top: 1em; /* Position the navbar at the top of the page */
  width: 100%; /* Full width */
}

.navbar a {
  float: left;
  display: block;
  color: black;
  text-align: center;
  padding: 0px 16px;
  text-decoration: none;
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
  background: none;
  overflow-x: hidden;
  color: black;
  margin-right: 333px
}

.sidenav a {
  text-decoration: none;
  font-size: 1.5em;
  display: block;
}

.sidenav a:hover {
  color: red;
}

.main {
  margin-left: 140px;
  font-size: 2em;
}
.topnav input[type=text] {
  float: right;
  padding: 6px;
  border: none;
  margin-top: 8px;
  margin-right: 16px;
  font-size: 17px;
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
