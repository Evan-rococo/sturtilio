<template>
  <Layout>
  
  <div class="container">
  <div class="left">
    <div class="item item1"><g-image src="~/static/Images/hrb7.jpg"/></div>
    <div class="item item3">
      <table><tr>
    <td><h2><g-link to="/">Conditions</g-link><br>
            <g-link to="/genre">Return to shop</g-link></h2></td>
    <td><h3>$13.91<br>
            <g-link to="/">Add to cart</g-link><br>
            </h3></td></tr>
</table>
</div>
      
    
</div><div class="right">
  <div class="item item2"> <h2>"Stand up for your rights" LP<br>
     Feel it <br>
     Guavo editionz <br>
     South africa '89 <br>
     Vinyl vg+ sleeve vg <br></h2>
  </div>
    
    <div class="item item4"> <p>A sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness. </br>
    <br>Death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion.. </br> 
    <br>Usually in a poignant but solemn manner. <br>Ballads are generally melodic enough to get the listener's attention but solemn manner. Ballads are generally melodic enough to get the listener's attention.</p></div>
    
    <div class="item item6"><table>
      <tr><td><h3>
           <audio id="music" preload="true">
  <source src="http://www.alexkatz.me/codepen/music/interlude.mp3">
			<source src="http://www.alexkatz.me/codepen/music/interlude.ogg">
	</audio>
<div id="audioplayer">
	<button id="pButton" class="play"></button>
  <div id="timeline">    Sample #1
  		  <div id="playhead"></div>
  </div>
</div><br>
            
            </h3></td></tr>
      </table>
      
    </div>
  </div>
</div>
	 </Layout>
</template>

<script>

export default {
  metaInfo: {
    title: 'Product'
  }
}

</script>


<style scoped>
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
  padding-top: 6em;
  margin-left: 26vw;
  margin-bottom: 8em;
  background-color:none;}

.left {
  width: 100%;
}

.right{
  width: 37%;}

@media (max-width: 33em) {
  .container {
    margin-bottom:8em;
    padding-top: 2em;
    background: none;}

  .item3{
    font-size: 1em;
  }
  .item {
  margin-bottom: 0em;
  text-align: left;
  background:none;
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
    margin-left:4.5vw;
    margin-right:5vw;
    margin-bottom:8em;
    margin-top: 1em;
    width: 90vw;
    background-color: none;
    }
}

.item {
  margin-bottom: 0em;
  text-align: left;
  background:none;
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
.item4, .item6{
  order: 2;
}
.item5, .item3{
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
  }
  .left{
    width: 63%;
    margin-right: 2em;
    max-width: 42vw;}

  .item1 {
    opacity: 100%;}
  .item3 {
    background-color: none;
    text-decoration: none;}

  
  .right{
    width: 36%;
    background-color: none;
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
  .left{
    width: 63%;
    margin-right: 2em;
    max-width: 450px;}

  .item1 {
    opacity: 100%;}
  .item3 {
    background-color: none;
    text-decoration: none;}

  
  .right{
    width: 33%;
    background-color: none;
  } 
}

#audioplayer{
	width: 30vw;
	height: 2em;
  float: right;
  margin-bottom: 1em;
}

#pButton{
    height:3.6em; 
    width: 0px;
    border: none;
    background-repeat: no-repeat;
    background-position: center;
    
}

.play{background: Sample text;}
.pause{background: Sample text ;}

#timeline{
	width: 100%;
	height: 1.34em;
	background: yellow;
  
}
#playhead{
	width: 18px;
	height: 1.34em;
	border-radius: 0%;
	background: red;

}

</style>