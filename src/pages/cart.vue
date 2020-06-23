<template>
  <Layout>
  
  <div class="container">


  <div class="left">
    <div class="item item1" style="margin-bottom:1.67em; padding:.34em;"> <table><tr>
    <td>"Title," artist, condition, product number
    </td>
    <td style="text-align:right;">Price
            </td></tr></table></div>
   
      
</div><div class="right" style="background-color:whitesmoke; padding:.34em;">
  <div class="item item2"><form action="/action_page.php">
  <div class="row">
    <div class="col-25" >
      <label for="name">Name</label>
    </div>
    <div class="col-75">
      <input type="text" id="fname" name="firstname" style="text-align:right; color:orchid; background-color:whitesmoke;" placeholder="">
    </div>
    <div class="col-25" >
      <label for="name">Street address</label>
    </div>
    <div class="col-75">
      <input type="text" id="fname" name="firstname" style="text-align:right; color:orchid; background-color:whitesmoke;" placeholder="">
    </div>
    <div class="col-25" >
      <label for="name">City</label>
    </div>
    <div class="col-75">
      <input type="text" id="fname" name="firstname" style="text-align:right; color:orchid; background-color:whitesmoke;" placeholder="">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="lname">Country</label>
    </div>
    <div class="col-75">
      <input type="text" id="lname" name="lastname" style="text-align:right; color:orchid; background-color:whitesmoke;" placeholder="">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="lname">Email address</label>
    </div>
    <div class="col-75">
      <input type="text" id="lname" name="lastname" style="text-align:right; color:orchid; background-color:whitesmoke;" placeholder="">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="subject">Additional notes</label>
    </div>
    <div class="col-75">
      <textarea id="subject" name="subject" placeholder="" style="height:9em; text-align:right; color:orchid; background-color: whitesmoke;" ></textarea>
    </div>
  </div>
  <div class="row">
    <input type="submit" style="font-family:tonii; font-size:1.34em; padding:.34em;" value="Order">
  </div>
  </form>
  </div>
    
    
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
}

table {
  border-collapse: collapse;
  width: 100%;
}

td {
  width: 50%;
  vertical-align: top;
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
  }

.left {
  width: 50%;
}

.right{
  width: 50%;}

  .item1 {
  padding-bottom: 1.67em;
  background-color: yellow;
}

@media (max-width: 33em) {
  .container {
    margin-bottom:0em;
    padding-top: 3.67em;
    background-color: white;
    }

 
  .item {
  margin-bottom: 0em;
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
}
@media (max-width: 48em) {
  .container {
    margin-left:4vw;
    margin-right:5vw;
    margin-bottom:3.67em;
    padding-top: 3.2em;
    width: 92vw;
    }
}

.item {
  margin-bottom: 0em;
  text-align: left;
  }

.item1 {
  padding-bottom: 1.67em;
}

.left {
  background-color:;
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
    margin-top: 3.67em;
    margin-left: 12em;
    margin-bottom: 3.67em;
  }
  .left{
    width: 60%;
    margin-right: 2em;
    max-width: 42vw;
    }

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
  } 
}
.item2 {
  font-size: 1em;
}
.item3 {
  margin-top:1.34em;
  line-height: 1em;  
}

.btn{
   font-size: 1em;
   cursor:pointer;
   display:inline-block;
   text-align: right;
   }

 .Sidebar1 {
  background:whitesmoke;
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

.container {
  display: flex;
  flex-direction: column;
  margin-top: 1.67em;
  margin-left: 26vw;
  margin-right: 0em;
  margin-bottom: 8em;
  width: 50vw;
  }

@media (max-width: 33em) {
  .container {
    }
 }

@media (max-width: 48em) {
  .container {
    margin-left:5vw;
    margin-right:5vw;
    margin-bottom:8em;
    margin-top: 4.1em;
    width: 90vw;
    }
  }

.col-25 {
  text-align: right;
  color: black;
  font-size: 1em;
  padding-top:.67em;
  padding-right:.67em;
  background-color:lime;
  text-align:right;
  background-color:whitesmoke;
  }

.col-75 {
  text-align:right;
  color:orchid;
  padding-right:.67em;
  background-color:whitesmoke;
  }

.left {
}

   
@media (min-width: 48em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
    }
  
  .container{
    display: block;
    margin-left: 22vw;
    margin-top:3.67em;
    margin-right: 2em;
    margin-left: 12em;
    width: 72vw;
    }

  .col-25 {
  text-align: right;
  color: black;
  font-size: 1em;
  }

  .col-75 {
  text-align: right;
  color: black;
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
    margin-top:4em;
    width: 64vw;
    }

  .col-25 {
  text-align: right;
  color: black;
  font-size: 1em;
}

.col-75 {
  text-align: right;
  color: black;
}
  }


mark {
  background-color: yellow;
  color: black;
  }

  * {
  box-sizing: border-box;
}

input[type=text], select, textarea {
  width: 100%;
  padding-bottom: 0em;
  border: 0px;
  resize: vertical;
  font-family: 'elmo';
  font-size: 1em;
  outline: none;
}

label {
  display: inline-block;
  outline: none;
}

input[type=submit] {
  background-color:whitesmoke;
  font-size: 1em;
  font-family: 'elmo';
  border: none;

  padding:0em;
  cursor: pointer;
  float: right;
  outline: none;
}

input[type=submit]:hover {
  outline: none;
  padding:0em;
}

</style>