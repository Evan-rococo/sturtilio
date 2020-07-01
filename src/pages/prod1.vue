<template>
  <Layout>
  
  <div class="container">
  <div class="left">
    <div class="item item1"><input class="native-hidden" type="checkbox" /></div>
    <div class="item item3" style="background-color:aqua; margin-top:1.34em;"><div>
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
      
  <div class="item item5" style="margin-top:0em;"></div></div>
      </div>
      

<div class="right">
  <div class="item item2" style="background-color:blue;">"Stand up for your rights" LP<br>
     Feel it <br>
     Guavo editionz <br>
     South africa '89 <br>
     Vinyl vg+ sleeve vg <br>
  </div>
    
    <div class="item item4" style="background-color:orange;"> A sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness. </br>
    <br>Death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion.. </br> 
    <br>Usually in a poignant but solemn manner. <br>Ballads are generally melodic enough to get the listener's attention but solemn manner. Ballads are generally melodic enough to get the listener's attention.</div>
    
    <div class="item item6" style="background-color:orchid; margin-top:1.67em;"><div>
        <h12 class style="font-family:Tonii; font-size:2em;">€13.92</h12><br>
          <g-link to="/" style="font-family:Tonii; font-size:2em; margin-bottom:3.67em;">Order</g-link><br>
          
     <section id="accordion">
			<div>
				<input type="checkbox" id="check-8" />
				<label for="check-8" style="font-size:1.34em;">Conditions</label>
				<article>
					<p>Pricing is a good topic. Everything considered (rarity, hype, condition, and the music itself), the pricing also reflects the time spent chasing down these records. Also included in the price is the number of shitty records I've bought in the gambling process of "discovering" something unknown.<br><br>
          If the record is listed on discogs, I list cheaper. If there are no other copies available online, I'll try to find a price where it can sell for more in the future.<br><br>
          I agree there is a sizeable speculativity, but I want to err on being conservative in my pricing.</p>
				</article>
			</div>
		</section>
       </div> 
       <g-link to="/genre" style="font-size:1.34em;">Back to shop</g-link></div>
       
        </div>
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
  background-color:;
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
  margin-top: 3.67em;
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
  padding-bottom: 0em;
}

@media (max-width: 33em) {
  .container {
    margin-bottom:0em;
    padding-top: 3.67em;
    background:none;
    }

 
  .item {
  margin-bottom: 0em;
  text-align: left;
  background:none;
  }

  
table {
  border-collapse: collapse;
  width: 92vw;
  background-color:none;
  margin-top:-27.34em;
}

.left {
    opacity: 66%;
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
}
@media (max-width: 48em) {
  .container {
    margin-left:4vw;
    margin-right:5vw;
    margin-bottom:3.67em;
    padding-top: 3.67em;
    width: 92vw;
    background-color:none;
    }
}

.item {
  margin-bottom: 0em;
  text-align: left;
  background:none;
  }

.item1 {
  padding-bottom: 0em;
}

.item2 {
  margin-top: 1em;
}

.left {
  opacity: 100%;
  }

.left, .right{
  display: contents;
}
.item1, .item2{
  order: 1;
}
.item4, .item5{
  order: 2;
}
.item3, .item6{
  order: 3;
}

   
@media (min-width: 48em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  
  .container{
    display: block;
    margin-left: 23vw;
    background-color: none;
    margin-top: 3.67em;
    margin-left: 12em;
    margin-bottom: 3.67em;
  }

table {
  border-collapse: collapse;
  width: 42vw;
  background-color:none;
  margin-top:-33em;
  margin-bottom:3.67em;
  margin-left: 12.08em;
  font-size:1em;
}

  .left{
    width: 60%;
    margin-right: 1.34em;
    max-width: 42vw;}

 .item1 {
  padding-bottom: em;
}

.item2 {
  margin-top: 0em;
}
  .right{
    width: 36%;
  } 
}

@media (min-width: 64em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  
  .container{
    display: block;
    margin-left: 27vw;
  }

table {
  border-collapse: collapse;
  width: 58vw;
  background-color:none;
  margin-top:-17.34em;
  margin-left: 27vw;
}

  .left{
    width: 60%;
    margin-right: 2em;
    max-width: 450px;}
  
  .right{
    width: 35%;
    background-color: none;
  } 
}
.item2 {
  font-size: 1.67em;
  margin-bottom: 1em;
}
.item3 {
  font-size: 1em;
  line-height: 1em;
  text-align: right;
}

.btn{
   font-size: 1.34em;
   line-height: 1.5em;
   cursor:pointer;
   display:inline-block;
   text-align: right;
   }

 .Sidebar1 {
  background:whitesmoke;
  line-height: 1em;
  padding:.67em;
      
        }
      

 .Sidebar1 {
    transform: translate3d(-200%, 0, 0);
    top: 3em;
    
  }
 
  .Sidebar1.open {
    transform: translate3d(0, 0, 0);
     .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  }

.btn{
   font-size: 1.25em;
   line-height: 1.5em;
   cursor:pointer;
   display:inline-block;
   text-align: right;
   }

   #accordion input {
	display: none;
}
#accordion label {
	background:white;
	
	cursor: pointer;
	display: block;
	margin-bottom: .0;
	padding: .1725em 0em;
	z-index: 20;
  font-size: 1.5em;
  line-height: 1em;
  background:none;
}
#accordion label:hover {
}

#accordion input:checked + label {
	background:none;
	font-size: 1.2
5em;
	margin-bottom: 0;
}
#accordion article {
	background:whitesmoke;
	height:0px;
	overflow:hidden;
	z-index:10;
}
#accordion article p {
	padding: 1em;
}
#accordion input:checked article {
}
#accordion input:checked ~ article {
	height: auto;
	margin-bottom: .125em;
}

mark {
  background-color: orchid;
  color: black;
  }

input[type="checkbox"] {
    content: url('http://placekitten.com/200/210');
    display: block;
    width: 200px;
    height: 200px;
    border:none;
}
input[type="checkbox"]:checked {
    content: url('/ececo/src/static/Images/p1.png');
}
.native-hidden {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none; }
 
</style>