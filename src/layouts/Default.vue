<template>

  <div class="layout">
    <div class="header">
  <a href="#default" class="logo"><g-link to="/">Hot request</g-link></a>
  <div class="header-right">
    <g-link to="/">Cart</g-link>
    <g-link to="/">Search</g-link>
  </div>
</div>
      <div class="Sidebar">
        <h2><g-link to="/">New stuff</g-link><br>
            <g-link to="/genre">afro</g-link><br>
            <g-link to="/genre">boogie</g-link><br>
            <g-link to="/genre">esoteric</g-link><br>
            <g-link to="/genre">pop music</g-link><br>
            <g-link to="/genre">reggae</g-link><br>
            <g-link to="/genre">contact</g-link>
            </h2>

      

</div>
<div class="Hamburger">
  <i class="Icon">
    <svg fill="#000000" height="18" viewBox="0 0 24 24" width="18" xmlns="http://www.w3.org/2000/svg">
        <path d="M0 0h24v24H0z" fill="none"/>
        <path d="M3 18h18v-2H3v2zm0-5h18v-2H3v2zm0-7v2h18V6H3z"/>
    </svg>
  </i>
</div>
    
    <slot/>
    <div class="footer">
    <div class="marquee">
        <p>Opening soon, sometime this month, god willing. Still a lot to do tbh</p>
    </div></footer></div>
  </div>
</template>

<script>
</script>


<style>
body {
  font-family: "Elmo";
  margin:0;
  line-height: 1.;
  width: 100%;
  text-decoration: none;
}

.h1 {
  font-family: "medi";
  font-size:  2em;
  text-decoration: none;
}

.p {
  font-family: "elmo";
  font-size: calc(16px + 1vw);
  line-height: calc(1.1em + 0.5vw);
  text-decoration: none;
}

h2 {
  font-family: "elmo";
  font-size: 1.5em;
  line-height: 1.33em;
  text-decoration: none;}

h3 {
  font-family: "elmo";
  text-align: right;
  font-size: 1.5em;
  line-height: 1.33em;
  text-decoration: none;}


.logo {
  font-family: "medi";
  font-size:  2em;
  letter-spacing: -0.05em;
  }

.layout {
  width: 100%;
  margin-right: 0em;
  padding-left: 0px;
  padding-right: 0vw;
  }

.nav__link {
  margin-left: 0px;
  text-decoration: none;
  color: black;
}

.header {
  overflow: hidden;
  margin-top: 1em;
  width: 100%;
  position: relative;
  left: 0;
  top: 0;
  background: none;
  
}

.header a {
  float: left;
  color: none;
  text-align: center;
  text-decoration: none;
  margin-left: 3.95vw;
 }


.sticky {
  position: fixed;
  top: 0;
  width: 100%;
}

.header a.logo {
  font-size: 2.67em;
}

.header a:hover {
  background-color:none;
  color: red;
}

.header a.active {
  background-color:none;
  color: black;
}

.header-right {
  float: right;
  background-color:none;
  font-size: 2em;
  margin-right: 9vw;
  background-color: none;
}


@media screen and (max-width: 64em) {
  .header a {
    background-color: none;
    margin-left: .86vw;
    float: left;
  }
   .header {
    background-color:none;} 
    
  .header-right {
  float: fixed;
  background-color: none;
}
    }

@media (max-width: 48em) {

  .header a {
    float: right;
    display: block;
    align-items: center;
    background-color:none;
    margin-right: .5em;
    margin-top:0.1em;
    }}
  .header {
    float: right;
    display: block;
    position: fixed;
    left: 0;
    top: 0; }
    
  .header-right {
  margin-top:0.96em;
  font-size: 1.5em;
  position: relative;
  left: 0;
  top: 0;
  background-color:none;
}

@media screen and (max-width: 33em) {
  .header a {
    float: right;
    display: block;
    text-align: right;
    mix-blend-mode: difference;
    background-color: none;
    margin-right: 3vw;
    position: relative;
    left: 0;
    top: 0;
  
  }
   .header {
    position: relative;
    left: 0;
    top: 0;
    background-color: none;} 
    
  .header-right {
  float: left;
  margin-left:3em;
  margin-top:-1.5em;
  position: fixed;
    left: 0;
    top: 0;
    background-color: tan;
}
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


/* Change background on mouse-over */
.navbar a:hover {
  color: red;
}

/* Main content */
.main {
  margin-top: 0px; /* Add a top margin to avoid content overlay */
}

body {
  position: relative;
}

.Sidebar {
  position: fixed;
  top: 5em;
  bottom: 0;
  left: 0;
  width: 16em;
  height: 21em;
  background:none; opacity: 100%;
  z-index: 0;
  margin-left: 8vw;
}
.Hamburger {
  position: fixed;
  margin-top: 3em;
  opacity: 0;
  z-index: 2;
}

@media (max-width: 48em) {
  .Sidebar {
    transform: translate3d(-100%, 0, 0);
    top: 3em;
  }
  .Hamburger {
    opacity: 1;
    margin-left:2vw;
    top: -1.8em;
  }
  .Sidebar.toggled {
    transform: translate3d(0, 0, 0);
  }
}
@media (max-width: 64em) {
  .Sidebar {
    position: fixed;
  top: 5em;
  bottom: 0;
  left: 0;
  width: 16em;
  height: 21em;
  background:none; opacity: 100%;
  z-index: 0;
  margin-left: 2vw;
  }
  }
.Button {
  position: absolute;
  top: 0.5em;
  right: 0.5em;
  width: 4em;
}


.main {
  font-size: 2em;
}
.topnav input[type=text] {
  float: right;
  border: none;
  margin-top: 1em;
  margin-right: 1.8em;
  margin-left: 3vw;
  position: relative;

}

.sticky {
  position: relative;
  top: 0;
  width: 100%}

@media screen and (max-width: 48em) {
  .topnav a, .topnav input[type=text] {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 1.2em;
  }
  .topnav input[type=text] {
  }
}

.marquee {
            height: 2em;
            overflow: hidden;
            position: relative;
            background: yellow;
            color: black;
            align-items:baseline;
        }
        
        .marquee p {
            position: fixed;
            width: 100%;
            height: 100%;
            margin: 0;
            line-height: 2em;
            text-align: center;
            -moz-transform: translateX(100%);
            -webkit-transform: translateX(100%);
            transform: translateX(100%);
            -moz-animation: scroll-left 1s linear infinite;
            -webkit-animation: scroll-left 1s linear infinite;
            animation: scroll-left 9s linear infinite;
        }
        
        @-moz-keyframes scroll-left {
            0% {
                -moz-transform: translateX(100%);
            }
            100% {
                -moz-transform: translateX(-100%);
            }
        }
        
        @-webkit-keyframes scroll-left {
            0% {
                -webkit-transform: translateX(100%);
            }
            100% {
                -webkit-transform: translateX(-100%);
            }
        }
        
        @keyframes scroll-left {
            0% {
                -moz-transform: translateX(100%);
                -webkit-transform: translateX(100%);
                transform: translateX(100%);
            }
            100% {
                -moz-transform: translateX(-100%);
                -webkit-transform: translateX(-100%);
                transform: translateX(-100%);
            }
        }
        
  .footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
}


</style>
