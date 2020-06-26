<template>

  <div class="layout">
    <div class="header">
  <a href="#default" class="logo"><g-link to="/">Hot request</g-link></a>
  <div class="header-right">
    <g-link to="/"></g-link>
    <g-link to="/"></g-link>
  </div>
</div>
      <div class="Sidebar" v-bind:class="{ open: isActive}" style="opacity:100%;">
        <g-link to="/">New stuff</g-link><br>
            <g-link to="/afro">afro</g-link><br>
            <g-link to="/genre">boogie</g-link><br>
            <g-link to="/genre">esoteric</g-link><br>
            <g-link to="/genre">pop music</g-link><br>
            <g-link to="/genre">reggae</g-link><br>
            <br>
            <g-link to="/faq">Faq</g-link><br>
            <g-link to="/contact">contact</g-link><br>
            <form class="example" style="font-size:1em;" action="/action_page.php" autocomplete="off">
  <input type="text" placeholder="search" name="search">
  <button type="submit"><i class="fa fa-search"></i></button>
</form>
       

      

</div>
<div class="Hamburger"  @click.prevent="toggleClass">
  <i class="Icon">
    <g-image src="~/static/d1.svg"/>
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
 export default {
        data: () => ({
            isActive: false
        }),
        methods: {
           toggleClass: function(event){
       this.isActive = !this.isActive;
    }
        }
    }
</script>

<style>
/* unvisited link */
a:link {
  color: red;
  text-decoration: none;
  text-emphasis: none;
  font-size:1em;
  line-height: 1em;
}

/* visited link */
a:visited {
  color: black;
}

/* mouse over link */
a:hover {
  color: red;
}

body {
  font-family: "Elmo";
  margin:0;
  line-height: 1.;
  width: 100%;
  }

.h1 {
  font-family: "medi";
  font-size:  2em;
  }

.h12 {
  font-family: "tonii";
  font-size:  1em;
  }

.p {
  font-family: "elmo";
  font-size: calc(16px + 1vw);
  line-height: calc(1.1em + 0.5vw);
  }
  
h2 {
  font-family: "elmo";
  font-size: 1.5em;
  }

h3 {
  font-family: "elmo";
  text-align: right;
  font-size: 1.5em;
  }

h4 {
  text-align: right;
  font-family: "elmo";
  font-size: 1.25em;
  }

h5 {
  font-family: "elmo";
  font-size: 1.25em;
  }

.logo {
  font-family: "Tonii-blacc";
  font-size:  2em;
  letter-spacing: -0.03em;
  text-shadow: 2px 2px 2px white;
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
  font-size: 2em;
  margin-right: 9vw;
  background-color: none;
  }

@media screen and (max-width: 64em) {
   .left, .right{
    display: inline-block;
    vertical-align: top;
    }
  
  .container{
    display: block;
    margin-left: 27vw;
    }
    
  .left{
    width: 63%;
    margin-right: 2em;
    max-width: 450px;
    }

  .item1 {
    opacity: 100%;
    }

  .item3 {
    background-color: none;
    text-decoration: none;
    }
  
  .right{
    width: 33%;
    background-color: none;
    }

  .header a {
    background-color: none;
    margin-left: .86vw;
    float: left;
    }

   .header {
    background-color:none;
    } 
    
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
    margin-top:0em;
    }

  .header {
    float: right;
    display: block;
    position: fixed;
    left: 0;
    top: 0;
    }
    
  .header-right {
    margin-top:0.96em;
    font-size: 1.5em;
    position: relative;
    left: 0;
    top: 0;
    background-color:none;
  }
}

@media screen and (max-width: 33em) {
  .container {
    background: red;
    }

.item {
  text-align: left;
  }

.left, .right{
  display: contents;
}
.item1, .item2{
  order: 1;
}
.item4, .item6{
  order: 2;
}
.item5, .item3{
  order: 3;
}
.header a {
  float: right;
  display: block;
  text-align: right;
  margin-right: 1.67vw;
  position: relative;
  left: 0;
  top: 0;
  }
.header {
  position: fixed;
  left: 0;
  top: 0;
} 
    
.header-right {
  float: left;
  margin-left:3em;
  margin-top:-1.5em;
  position: fixed;
  left: 0;
  top: 0;
  }
}

form.example input[type=text] {
  font-family: 'elmo';
  font-size: 1.67em;
  float: left;
  width: 100%;
  padding-left:0em;
  background: none;
  text-decoration: black;
}

form.example button {
  float: left;
  width: 10%;
  padding: 0px;
  background: orange;
  color: none;
  border: none;
  cursor: pointer;
  margin-left:0em;
  outline: 0px solid transparent;
  text-decoration: black !important;
}

form.example button:hover {
  background: red;
  border: none;
}

form.example::after {
  content: "";
  clear: both;
  display: table;
  font-family: 'elmo';
  text-decoration: black;
}

@font-face {
    font-family: 'Elmo';
    src: url('../static/elmer-webfont.woff') format('woff'), /* Modern Browsers */
         url('../static/elmer-webfont.ttf') format('truetype'); /* Safari, Android, iOS */
             font-style: normal;
    font-weight: normal;
    text-rendering: optimizeLegibility;}

@font-face {
    font-family: 'Tonii-blacc';
    src: url('../static/Tonii-blacc.woff') format('woff'), /* Modern Browsers */
         url('../static/Tonii-blacc.ttf') format('truetype'); /* Safari, Android, iOS */
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
  margin-top: 0px;}
.Sidebar {
  background:none; opacity: 100%;
  position: fixed;
  top: 4.34em;
  bottom: 0;
  left: 0;
  z-index: 0;
  margin-left: 8vw;
  font-size: 1.67em;
  width: 7em;
}
.Hamburger {
  position: fixed;
  margin-top: 3em;
  opacity: 0;
  z-index: 2;
}
@media (max-width: 48em) {

  .header a {
  float: right;
  display: block;
  text-align: right;
  margin-right: 1.67vw;
  position: relative;
  left: 0;
  top: 0;
  }
  .Sidebar {
    transform: translate3d(-100%, 0, 0);
    top: 3em;
    
  }
  .Hamburger {
    opacity: 1;
    margin-left:3vw;
    top: -2.2em;
  }
 
  .Sidebar.open {
    transform: translate3d(0, 0, 0);
     .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  
  .container{
    display: block;
    margin-left: 23vw;
  }
  .left{
    width: 63%;
    margin-right: 2em;
    max-width: 42vw;}
  .item1 {
    opacity: 100%;
    }

  .item3 {
    background-color: none;
    text-decoration: none;
    }
  
  .right{
    width: 36%;
    background-color: none;
  } 
  
  .topnav a, .topnav input[type=text] {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 1.2em;
        }
      }
    }

    form.example input[type=text] {
  font-family: 'elmo';
  font-size: 1em;
  float: left;
  width: 100%;
  border: none;
  outline: 0px solid transparent;
  padding-left:0em;
  background:none;
  text-decoration: black;
}


@media (min-width: 48em){
  
  .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  
  .container{
    display: block;
    margin-left: 23vw;
  }
  .left{
    width: 63%;
    margin-right: 2em;
    max-width: 42vw;
    }

  .item1 {
    opacity: 100%;
    }

  .item3 {
    background-color: none;
    text-decoration: none;}
  
  .right{
    width: 36%;
    background-color: none;
    } 

    form.example input[type=text] {
  font-family: 'elmo';
  font-size: 1em;
  float: left;
  width: 90%;
  border: none;
  outline: 0px solid transparent;
  padding-left:0em;
  background: none;
  text-decoration: black;
}
  }

@media (max-width: 64em) {
  .Sidebar {
  position: fixed;
  background:none;
  top: 4.34em;
  bottom: 0;
  left: 0;
  background:none;
  opacity: 100%;
  z-index: 0;
  margin-left: 2.34vw;
  width: 6em;
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
  width: 100%;}

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
table, td, th {
  border: 0px solid black;
}
table {
  border-collapse: collapse;
  width: 100%;
}
td {
  width: 50%;
  vertical-align: top;
  background-color:none;
}
img {
  max-width: 100%;
  display: block;
}
p {
  margin: 0 0 0 0;
}
.container {
  display: flex;
  flex-direction: column;
  margin-left: 26vw;
  margin-bottom: 8em;
  background-color:none;}
.left {
  width: 100%;
}
.right{
  width: 37%;}
  
   @media (max-width: 48em) {
     .Sidebar {
      background:yellow;
      margin-left:-.0em;
      margin-top: .05em;
      padding-left:.67em;
      padding-top: .67em;
      padding-bottom: .34em;
      padding-right: .34em;
      height: 11.67em;
      width: 7em;
        }
      }

</style>