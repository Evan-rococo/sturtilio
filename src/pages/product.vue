<template>
  <Layout>
    <div class="Sidebar" v-bind:class="{ open: isActive}" style="opacity:100%; line-height:1em;">
        <g-link to="/newstuff">New stuff</g-link><br>
            <g-link to="/afro">afro</g-link><br>
            <g-link to="/boogie">boogie</g-link><br>
            <g-link to="/esoteric">esoteric</g-link><br>
            <g-link to="/pop">pop music</g-link><br>
            <g-link to="/reggae">reggae</g-link><br>
             <br>
            <g-link to="/faq">Faq</g-link><br>
            <g-link to="/contact">contact</g-link><br>
            <br>
            <g-link to="/cart">Cart (0)</g-link><br>
            <form class="example" action="/action_page.php" autocomplete="off">
  <input type="text" placeholder="search" name="search" >
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
  
  <div class="container">
  <div class="left">
    <div class="item item1"><g-image src="~/static/Images/hrb7.jpg"/></div>
    <div class="item item3">
      
    <div style="text-align:right;">
        <h12 class style="font-family:Tonii; font-size:1.34em;">€129.00</h12><br>
          <g-link to="/cart" style="font-family:Tonii; font-size:1.34em;">Add to cart</g-link><br>
             <section id="accordion" style="margin-top:.34em;">
			<div>
				<input type="checkbox" id="check-3" />
				<label for="check-3" style="font-size:1em; padding-bottom:0.34em;">Shipping</label>
				<article>
					<p style="font-size:.8em; line-height:1em; background-color:pink; padding:.67em;">Payments can be made either by Paypal or, in the case of Swedish residents, Swish.</p>
				</article>
			</div>
			<div>
				<input type="checkbox" id="check-4" />
				<label for="check-4" style="padding-bottom:0.34em; font-size:1em;">Conditions</label>
				<article>
					<p style="font-size:.8em; line-height:1em; background-color:pink; padding:.67em;">In your paypal payment, a tracking number will be added and can be searched <mark><g-link to="https://www.postnord.se/en/our-tools/track-and-trace2">right here.</g-link></mark>PostNord delivers within 5 working days in the EU and somewhere around 6-8 in North america and Asia.</p>
				</article>
			</div>
		</section>
    </div>

              <div class="item item5" style="margin-top:.67em;">
                
        
          
</div>
</div>
      
    
</div><div class="right">
  <div class="item item2">"Stand up for your rights" LP<br>
     Feel it <br>
     Guavo editionz <br>
     South africa '89 <br>
     Vinyl vg+ sleeve vg <br>
  </div>
    
    <div class="item item4" style="margin-bottom:3.67em; font-size:1em;"> A sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness. </br>
    <br>Death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion.. </br> 
    <br>Usually in a poignant but solemn manner. <br>Ballads are generally melodic enough to get the listener's attention but solemn manner. Ballads are generally melodic enough to get the listener's attention.</div>
    
    <div class="item item6" style="text-align:right;"><div>
          <audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
   Your browser does not support the audio element.
</audio>
<a class="btn" id="nyan-btn">Libreville (Rough mix)</a><br>

<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
   Your browser does not support the audio element.
</audio>
<a class="btn" id="nyan-btn">Ekweghele</a><br>
          
<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
   Your browser does not support the audio element.
</audio>
<a class="btn" id="nyan-btn">New Casino</a><br>
          
          
          </div>
        </div>
      </div>
    </div>

<div class="row3">
  <h5 style="margin-bottom:.34em;">Also very nice..</h5>
  <div class="column left3">
    <g-image src="~/static/Images/hrb17.jpg"/>
    <p style="margin-top:.34em;">"Böhöbé Spirits Music" LP</p>
  </div>
  <div class="column middle3">
    <g-image src="~/static/Images/hrb18.jpg"/>
    <p style="margin-top:.34em;">Broken ally 7"</p>
  </div>
  <div class="column right3">
    <g-image src="~/static/Images/hrb12.jpg"/>
    <p style="margin-top:.34em;">"Ich träume so leise von dir" LP</p>
  </div>
</div>


  </Layout>
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


<style scoped>

table, td, th {
  border: 0px solid black;
}

table {
  border-collapse: collapse;
  width: 92vw;
  background-color:none;
  margin-top:-27.34em;
  margin-left: 4vw;
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
  margin-top: 2.34em;
  margin-left: 26vw;
  margin-bottom: 0em;
  background-color:none;
  }

.left {
  width: 100%;
}

.right{
  width: 37%;}

  .item1 {
  padding-bottom: 1.67em;
}

@media (max-width: 33em) {
  .container {
  margin-bottom:0em;
  padding-top: 3.67em;
  background:none;}
 
  .item {
  margin-bottom: 0em;
  text-align: left;
  background:none;}
  
  table {
  border-collapse: collapse;
  width: 92vw;
  background-color:none;
  margin-top:-27.34em;}

.left {
    opacity: 66%;}

.left, .right{
  display: contents;}

.item1, .item2{
  order: 1;}

.item4, .item6{
  order: 2;}

.item5, .item3{
  order: 3;}

.column {
  float: left;
  height: 47vw;
}

.row3 {
  margin-left: 2vw;
  margin-right: 2vw;
  margin-bottom:2em;
  }

.right3 {
  width: 47vw;
  text-align: right;}

.middle3 {
  width:0vw;
  text-align: right;}

.left3 {
  width: 47vw;
  text-align: right;
  margin-right:2vw;}
  
  }

@media (max-width: 48em) {
  .container {
    margin-left:2vw;
    margin-right:2vw;
    margin-bottom:3.67em;
    padding-top: 3.67em;
    width: 96vw;}


.item {
  margin-bottom: 0em;
  text-align: left;
  background:none;}

.item1 {
  padding-bottom: 1em;}

.item6 {
  margin-right:0em;}

.left {
  opacity: 100%;}

.left, .right{
  display: contents;}

.item1, .item2{
  order: 1;}
.item4, .item6{
  order: 2;}
.item5, .item3{
  order: 3;}

.column {
  float: left;
  height: 4em;}

.row3 {
  margin-left: 2vw;
  margin-right: 2vw;
  margin-bottom:5em;
  padding:0em;
  background-color:none;
  height: 56vw;}

.right3 {
  width: 47vw;
  text-align: right;}

  .middle3 {
  text-align: right;
  width:0vw;
}

.left3 {
  text-align: right;
  width: 47vw;
  margin-right:2vw;}
}
   
@media (min-width: 48em){
  .left, .right{
    display: inline-block;
    vertical-align: top;}
  
  .container{
    display: block;
    margin-left: 24.67vw;
    background-color: none;
    margin-top: 2.3em;
    margin-bottom: .67em;
    height: 36em;
    background-color:yellow;}

table {
  border-collapse: collapse;
  width: 42vw;
  background-color:none;
  margin-top:-33em;
  margin-bottom:3.67em;
  margin-left: 12.08em;
  font-size:1em;}

  .left{
    width: 43%;
    margin-right: 1.5vw;
    max-width: 42vw;}

 .item1 {
  padding-bottom: 0em;}

.item6 {
  background-color:lime;}

  .right{
    width: 53%;
    background-color: red;} 
  
  .column {
  float: left;
  height: 36vw;
}

.row3 {
  margin-left:23vw;
  margin-bottom:5em;
  background-color:none;}

.right3 {
  width: 23.8vw;
  text-align: right;}

  .middle3 {
  width: 23.8vw;
  text-align: right;
  margin-right:2vw;
}

.left3 {
  width: 23.8vw;
  text-align: right;
  margin-right:2vw}
}

@media (min-width: 64em){
    .column {
  float: left;
  height: 21em;
}

.row3 {
  margin-left:24.67vw;
  margin-bottom:30vw;
  background-color:none;}

.right3 {
  width: 23.2vw;
  text-align: right;}

  .middle3 {
  width: 23.2vw;
  margin-right:2vw;
}

.left3 {
  width: 23.2vw;
  margin-right:2vw}

  .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  
  .container{
    display: block;
    margin-left: 24.67vw;
    background-color: none;
    margin-top: 2.34em;
    height: 40em;
    width: 78vw;
  }

table {
  border-collapse: collapse;
  width: 58vw;
  background-color:none;
  margin-top:-17.34em;
  margin-left: 27vw;
}

  .left{
    width: 40%;
    margin-right: 1.67vw;
    max-width: 450px;}
  
  .right{
    width: 52%;
    background-color: none;} 
}
.item2 {
  font-size: 1.67em;
  margin-bottom: 1.5em;}

.item3 {
  margin-top:1.34em;
  font-size: 1.34em;
  line-height: 1em;}

.btn{
   font-size: 1.34em;
   line-height: 1.5em;
   cursor:pointer;
   display:inline-block;
   text-align: right;
   }

 .Sidebar1 {
  line-height: 1em;
  padding:.67em;}
      

 .Sidebar1 {
    transform: translate3d(-200%, 0, 0);
    top: 3em;}
 
  .Sidebar1.open {
    transform: translate3d(0, 0, 0);
    .left, .right{
    display: inline-block;
    vertical-align: top;}
  }

  .btn{
   font-size: 1.25em;
   line-height: 1.5em;
   cursor:pointer;
   display:inline-block;
   text-align: right;}

  #accordion input {
	display: none;}

#accordion label {
	background:red;
	cursor: pointer;
	display: block;
	margin-bottom: .0;
	padding: .1725em 0em;
	z-index: 20;
  font-size: 1.5em;
  line-height: 1em;
  background:none;}

#accordion label:hover {
}

#accordion input:checked + label {
	background:none;
	font-size: 1.25em;
	margin-bottom: 0;}

#accordion article {
	background: none;
	height:0px;
	overflow:hidden;
	z-index:10;}

#accordion article p {
	padding: .67em 0em;
}
#accordion input:checked article {
}
#accordion input:checked ~ article {
	height: auto;
	margin-bottom: .125em;}

  @media (max-width: 48em) {
     .Sidebar {
      background:yellow;
      margin-left:-.0em;
      padding-left:.34em;
      padding-top: .5em;
      padding-bottom: .34em;
      padding-right: .34em;
      height: 12.67em;
      width: 7em;
      top:3.15em;}
      }


 @media (min-width: 48em) {
     .Sidebar {
      position: fixed;
      background:none;
      top: 3.56em;
      bottom: 0;
      left: 0;
      background:none;
      opacity: 100%;
      z-index: 0;
      width: 6em;
        }
      }

  @media (min-width: 64em) {
     .Sidebar {
      position: fixed;
      background:none;
      top: 3.56em;
      bottom: 0;
      left: 0;
      background:none;
      opacity: 100%;
      z-index: 0;
      width: 6em;
      margin-left:7.34vw;
        }
      }

</style>