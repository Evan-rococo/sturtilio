<template>
  <Layout>
  
  <div class="container">
  <div class="left">
    <div class="item item1" style="margin-bottom:1.34em;"><g-link to="/product/">
    <g-image src="~/static/metal.gif"/>
    </g-link></div>
  </div><div class="right">
    <div class="item item4"> <p>Here it comes, the site is all fixed and online. The idea here is to keep pumping this place full of hot records to sell.<br><br>
    As of today, I would guess this should be as minimium viable product in 10 days or so. I need to get JS running so audio player works. I need to get instagram going too. Mailchimp, etc. So 10 days is about right.</p></div>
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
</script>


<style scoped>

.container {
  display: flex;
  flex-direction: column;
  padding-top: 3.67em;
  margin-left: 26vw;
  margin-right: 2em;
  margin-bottom: 8em;
  background-color:none;
  }

.left {
  width: 100%;
  }

.right{
  width: 37%;
  }

@media (max-width: 33em) {
  .container {
    margin-bottom:8em;
    padding-top: 3.67em;
    background:none;
    }

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
    margin-left:5vw;
    margin-right:5em;
    margin-bottom:8em;
    margin-top: 3.67em;
    width: 90vw;
    background-color:none;
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
    margin-left: 22vw;
    background-color: none;
    margin-right: 2em;
    margin-left: 12em;
    }

  .left{
    width: 56%;
    margin-right: 2em;
    max-width: 42vw;
    }

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
}

@media (min-width: 64em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
    }
  
  .container{
    display: block;
    margin-left: 27vw;
    margin-right: 2em;
    }

  .left{
    width: 63%;
    margin-right: 2em;
    max-width: 36vw;
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
  }


mark {
  background-color: yellow;
  color: black;
  }
</style>