<template>
  <Layout>
    <div class="sidenav">
   <g-link to="/genre1/">new stuff</g-link>
  <g-link to="/genre1/">afro</g-link>
  <g-link to="/genre1/">boogie</g-link>
  <g-link to="/genre1/">esoteric</g-link>
  <g-link to="/genre1/">pop music</g-link>
</div>
<div class="flex_container" style= "margin-top:5em;margin-left:12em;">
  <div class="flex_item_left">
    <g-image src="~/static/Images/hrb7.jpg" width="450;"/>
      <div class="h2" style= "text-align:right;">sample #1</div>
      <div class="h2" style= "text-align:right;">sample #2</div>
      <div class="h2" style= "text-align:right;">sample #3</div>
  </div>
  <div class="flex_item_right">
     <h2>Stand up for your rights LP </br>
     Feel it </br>
     Guavo editionz </br>
     South africa '89 </br>
     Vinyl vg+ sleeve vg </br>



     </h2>
       <p>pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion, usually in a poignant but solemn manner.[1] <br>Ballads are generally melodic enough to get the listener's attention.[2] ant but solemn manner.[1] Ballads are generally melodic enough to get the listener's attention.[2]</p>
       <h2><mark>Add to cart</mark></h2>
       <h2><mark>Return to shop</mark></h2>

  </div>
  </div>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hot request'
  }
}
</script>

<style>

.h2 {
  font-family: "elmo";
  font-size: 2.5vw;
  text-align: right;
  line-height: 3vw;
}

.home-links a {
  margin-right: 1rem;
}
.flex_container {
  display: flex;
  width: 100%;
}
.flex_item_left {
  width: 400px;
  background: none;
}
.flex_item_right {
  flex: 1;
  background: none;
  padding-left:6em;
  
}
</style>
