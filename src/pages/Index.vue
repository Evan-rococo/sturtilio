<template>
  <Layout>
  
  <div class="container">
  <div class="left">
    <div class="item item1"><g-image src="~/static/Images/hrb8.jpg"/></div>
  </div><div class="right">
    <div class="item item4"> <p>A sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion, usually in a poignant but solemn manner.</br>
    <br>Ballads are generally melodic enough to get the listener's attention.[2] ant but solemn manner.[1] Ballads are generally melodic enough to get the listener's attention.[2]</p></div>
  </div>
</div>
	

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'New stuff'
  }
}
for(let e of document.getElementsByClassName('item')) {
  e.style.minHeight = Math.floor(15 + Math.random() * 72) + 'px';
}
</script>
<style scoped>

html {
  font: "elmo";
}

img {
  max-width: 100%;
  display: block;
}

p {
  margin: 0 0 0 0;
}


@font-face {
    font-family: 'Elmo';
    src: url('../static/elmer-webfont.woff') format('woff'), /* Modern Browsers */
         url('../static/elmer-webfont.ttf') format('truetype'); /* Safari, Android, iOS */
             font-style: normal;
    font-weight: normal;
    text-rendering: optimizeLegibility;}

.container {
  display: flex;
  flex-direction: column;
  padding-top:5em;
  margin-left: 12vw;
}
.item {
  margin-bottom: 0em;
  text-align: left;
  background:none;
  padding: 0em;
  min-width: 280px;
  max-width: 450px;
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


@media (min-width: 60em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  
  .container{
    display: block;
  }
  .left{
    width: calc(67% - 0.5em);
    margin-right: 1em;
    margin-bottom: 4em;
    max-width:450px;
    max-height: 450px;
  }
  .right{
    width: 27%;
  }
}

</style>