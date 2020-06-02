<template>
  <Layout>
  
  <div class="container">
  <div class="left">
    <div class="item item1"><g-image src="~/static/Images/hrb7.jpg"/></div>
    <div class="item item3" style="margin-bottom: 0.33em;">
      <h3>sample #1</h3>
      <h3>sample #2</h3>
      <h3>sample #3</h3></div>
      
    <div class="item item5"></div>
  </div><div class="right">
    <div class="item item2"> <h2>Stand up for your rights LP </br>
     Feel it </br>
     Guavo editionz </br>
     South africa '89 </br>
     Vinyl vg+ sleeve vg </br>
    </h2></div>
    <div class="item item4"> <p>A sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness. </br>
    <br>Death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion.. </br> 
    <br>Usually in a poignant but solemn manner. <br>Ballads are generally melodic enough to get the listener's attention but solemn manner. Ballads are generally melodic enough to get the listener's attention.</p></div>
    <div class="item item6"><div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>  
</div></div>
  </div>
</div>
	

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Home'
  }
}
for(let e of document.getElementsByClassName('item')) {
  e.style.minHeight = Math.floor(25 + Math.random() * 72) + 'px';
}
</script>
<style scoped>


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
  width:100%;
  padding-top: 5em;
  margin-left: 12vw;

}
.item {
  margin-bottom: 0em;
  text-align: left;
  background:none;
  padding: 0em;
}
.left, .right{
  display: contents;
}
.item1, .item2{
  order: 1;
}
.item3, .item4{
  order: 2;
}
.item5, .item6{
  order: 3;
}


@media (min-width: 36em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  
  .container{
    display: block;
  }
  .left{
    width: calc(67% - 0.5em);
    padding-right: 3em;
    max-width:450px;
    min-width: 280px;

  }
  .right{
    width: 27%;
    max-width:600px;
  }
}

</style>