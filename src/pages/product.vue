<template>
  <Layout>
  
  <div class="container">
  <div class="left">
    <div class="item item1"><g-image src="~/static/Images/hrb7.jpg"/></div>
    <div class="item item3" style="font-size:1.25em">
      <table><tr>
    <td><g-link to="/">Conditions</g-link><br>
            <g-link to="/genre">Return to shop</g-link></td>
    <td style="text-align:right;"><g-link to="/">$13.92</g-link><br>
            <g-link to="/">Add to cart</g-link><br>
            </td></tr>
</table>
</div>
      
    
</div><div class="right">
  <div class="item item2">"Stand up for your rights" LP<br>
     Feel it <br>
     Guavo editionz <br>
     South africa '89 <br>
     Vinyl vg+ sleeve vg <br>
  </div>
    
    <div class="item item4" style="margin-bottom:3.67em;"> <p>A sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness. </br>
    <br>Death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion.. </br> 
    <br>Usually in a poignant but solemn manner. <br>Ballads are generally melodic enough to get the listener's attention but solemn manner. Ballads are generally melodic enough to get the listener's attention.</p></div>
    
    <div class="item item6" style="text-align:right;"><table>
      <tr><td>
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
          
          
            </td></tr>
          </table>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  
  metaInfo: {
    
    title: 'Product'}
}
</script>


<style scoped>

table, td, th {
  border: 0px solid black;
  background-color:;
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
  padding-top: 0em;
  margin-left: 26vw;
  margin-bottom: 8em;
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
    margin-bottom:8em;
    padding-top: 3.67em;
    background: none;
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
    margin-left:4vw;
    margin-right:5vw;
    margin-bottom:8em;
    margin-top: 7.34em;
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
  padding-bottom: 1.67em;
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
    background-color: none;
    margin-top: 3.67em;
    margin-left: 12em;
  }
  .left{
    width: 60%;
    margin-right: 2em;
    max-width: 42vw;}

 .item1 {
  padding-bottom: 0em;
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
  margin-bottom: 1.5em;
}
.item3 {
  margin-top:1.34em;
  line-height: 1.5em;
  background-color: none;
}

.btn{
   font-size: 1.25em;
   line-height: 1.5em;
   cursor:pointer;
   display:inline-block;
   text-align: right;
   }
</style>