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
    <div class="item item1" style="margin-bottom:.34em;">
      
      <g-link to="/product/">
    <g-image src="~/static/metal.gif"/>
    </g-link></div>
    <div class="item item2"> <p style="margin-bottom:1.34em; font-size: 1em; text-align:right;transform: rotate(0deg)">Last updated: June 31, 2020 01:19am</p></div>
  </div>

  <div class="right">
    <div class="item item4"> <p>Here it comes, the site is all fixed and online. The idea here is to keep pumping this place full of hot records to sell.<br><br>
    As of today, I would guess this should be as minimium viable product in 10 days or so. I need to get JS running so audio player works. I need to get instagram going too. Mailchimp, etc. So 10 days is about right.<br><br>
    Right now, I'm mostly excited about the Elle et moi 12" from Belgian. I can't remember the artist name, but it's definitely high on my list and hasn't sold on discogs since the last copy i got in 2018. </p> <div class="video-container">
  <iframe src="https://www.youtube.com/embed/N07ow4LDWfU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div></div>
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

.container {
  display: flex;
  flex-direction: column;
  padding-top: 0em;
  margin-left: 26vw;
  margin-right: 2em;
  margin-bottom: 4em;
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
    padding-top: 2.34em;
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
    margin-left:2vw;
    margin-bottom:4em;
    margin-top: 4.34em;
    width: 96vw;
    background-color:none;
    padding-top: 1.67em;
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
    background-color: none;
    margin-left: 12em;
    width: 96vw;
    margin-top: 2.34em;
    
    }

  .left{
    width: 30%;
    margin-right: 2.67vw;
    }

  .item1 {
    opacity: 100%;
    }
    
  .item3 {
    background-color: none;
    text-decoration: none;
    }

  .right{
    width: 40vw;
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
    margin-left: 24.67vw;
    margin-right: 2.67vw;
    width: 96vw;
    }

  .left{
    width: 58%;
    margin-right: 2vw;
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
    width: 38%;
    background-color: none;
    } 
  }


mark {
  background-color: yellow;
  color: black;
  }
  
.video-container {
    overflow: hidden;
    position: relative;
    width:100%;
}

.video-container::after {
    padding-top: 56.25%;
    display: block;
    content: '';
}

.video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    margin-top:1.67em;
    z-index: -3;
}

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
      top: 3.15em;
        }
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