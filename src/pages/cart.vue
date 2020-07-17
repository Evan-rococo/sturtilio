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
            <mark style="padding:.1725em; mix-blend-mode: darken;"><g-link>Cart (2)</g-link></mark><br>
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

<h3>In your paypal payment, a tracking number will be added and can be searched right here.PostNord delivers within 5 working days in the EU and somewhere around 6-8 in North america and Asia.</h3>
<div class="row">
  <div class="column left">
    <g-image src="~/static/Images/hrb7.jpg"/>
  </div>
  <div class="column middle">
    <h5 style="margin-top:.34em;">"Stand up for your rights" LP<br>
     Feel it <br>
     Guavo editionz <br>
     South africa '89 <br>
     Vinyl vg+ sleeve vg <br></h5>
  </div>
  <div class="column right">
    <h4 style="margin-top:.34em;">$120.99</h4>
    <hi style="text-align: right;font-size: 1.25em; margin-top:-1em;">Remove</hi>
  </div>
</div>

    

<div class="row" style="margin-top:0em;">
  <div class="column left">
    <g-image src="~/static/Images/hrb10.jpg"/>
  </div>
  <div class="column middle">
    <h5 style="margin-top:.34em;">"Sun tan club" LP<br>
     For light tanning <br>
     Guavo editionz <br>
     Japan '86 <br>
     Vinyl vg+ sleeve vg <br></h5>
  </div>
  <div class="column right">
    <h4 style="margin-top:.34em;">$199.99</h4>
    <hi style="text-align: right;font-size: 1.25em; margin-top:-1em;">Remove</hi>
  </div>
  </div>
</div>






<div class="row1" style="margin-top:0em;">
  <div class="column left1">
  </div>
  <div class="column middle1">
    <h5 style="margin-top:.34em;">Shipping</h5>
  </div>
  <div class="column right1">
    <h4 style="margin-top:.34em;">$120.00</h4>
  </div>
  </div>
</div>


<div class="row1" style="margin-top:0em; margin-bottom: 2em;">
  <div class="column left1">
  </div>
  <div class="column middle1">
    <h5 style="margin-top:.34em;">Total</h5>
  </div>
  <div class="column right1">
    <h4 style="margin-top:.34em;">$320.99</h4>
  </div>
  </div>
</div>


 <form action="/action_page.php">
  <div class="row2">
    <div class="col-25" style="margin:0em;">
      <label for="name">Name</label>
    </div>
    <div class="col-75">
      <input type="text" id="fname" name="firstname" style="text-align:right; background-color:whitesmoke;">
    </div>
  </div>
  <div class="row2">
    <div class="col-25">
      <label for="lname">Email address</label>
    </div>
    <div class="col-75" style="text-align:right; margin:0em;">
      <input type="text" id="lname" name="lastname" style="text-align:right; background-color:whitesmoke;" placeholder="">
    </div>
  </div>
  <div class="row2">
    <div class="col-25" style="text-align:right; margin:0em;" >
      <label for="topic">Topic</label>
    </div>
    <div class="col-75">
      <select id="topic" name="topic" style="color:black; background-color:whitesmoke;">
        <option value="request"></option>
        <option value="request">Make a request</option>
        <option value="before">Before order</option>
        <option value="after">After order</option>
      </select>
    </div>
  </div>
  <div class="row2">
    <div class="col-25">
      <label for="subject">Additional info</label>
    </div>
    <div class="col-75">
      <textarea id="subject" name="subject" placeholder="" style="text-align:right; background-color:whitesmoke;; height:3em;" ></textarea>
    </div>
  </div>
   <div class="row2" style="margin-bottom:8em;">

    <div class="col-25" style="text-align:right; font-size:1.5em; margin-top:0em; padding-bottom:2em; background-color:whitesmoke;" >
      <input type="submit" style="background-color:whitesmoke;" value="Checkout">
    </div></div>
  
  </form>
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


<style>
.container {
  display: flex;
  flex-direction: column;
  margin-left: 26vw;
  margin-right: 0em;
  margin-bottom: 8em;
  width: 50vw;
  }

@media (min-width: 48em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
    }

    .row {
margin-right:4vw;
    }
  
  .container{
    display: block;
    margin-left: 22vw;
    margin-top:2.34em;
    margin-right: 2em;
    margin-left: 12em;
    width: 64vw;
    }

  .col-25 {
  text-align: right;
  color: black;
  font-size: 1.34em;
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
  
    .row {
margin-right:7.34vw;
    }

  .container{
    display: block;
    margin-left: 24.67vw;
    width: 62vw;
    height:48em;
    }

  .col-25 {
  text-align: right;
  color: black;
  
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
  background-color: none;
}

label {
  display: inline-block;
  outline: none;
}

input[type=submit] {
  background-color:none;
  font-size: 1em;
  font-family: 'tonii';
  border: none;

  padding:0em;
  cursor: pointer;
  float: right;
  outline: none;
}

input[type=submit]:hover {
  background-color:none;
  outline: none;
  padding:0em;
}

{
  box-sizing: border-box;
}



/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
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
      top:3.15em;
      z-index: 2;
        }

.column {
  float: left;
  height: calc(8em + 5vw);}

.row {
  margin-left: 2vw;
  margin-right: 2vw;
  margin-bottom: 2vw;
  align-content: center;
  width: 96vw;
  background-color: none;}

.row1 {
  margin-left: 2vw;
  margin-right: 2vw;
  height: 2em;
  align-content: center;
  width: 96vw;
  background-color: none;
  }

.row2 {
  padding-top:.67em;
  padding-right: .67em;
  margin-left: calc(8.8em + 9vw);
  margin-right: 2vw;
  background-color:whitesmoke;}

 .col-25 {
  text-align: right;
  color: black;
  margin: 0em;
  padding:0em;
  font-size: 1.25em;
  font-weight: bold;
  background-color: whitesmoke;
  }

.col-75 {
  text-align: right;
  color: black;
  margin: 0em;
  padding:0em;
  font-size: 1.25em;
  font-weight: bold;
  }



.right {
  position: absolute;
  right: 2vw;
  width: 5em;
  height: 4em;
  background-color: none;
  }

.right1 {
  position: absolute;
  right: 2vw;
  width: 5em;
  height: 2em;
  }

.middle {
  width: 48vw;
  background-color: none;}

.middle1 {
  width: 48vw;
  height: 2em;
  background-color: none;
}
  
.left {
  width: calc(8em + 5vw);
  margin-right:4vw;}

.left1 {
  width: calc(8em + 7vw);
  height: 2em;
  margin-right:2vw;}

.left2 {
width: calc(8em + 5vw);
  height: 2em;}

hi {
  z-index:-2;
  background-color: yellow;
  position: absolute;
  right:0vw;
}


h3 {
  margin-left: 2vw;
  margin-right: 2vw;
  font-size:1.25em;
  margin-top: 4.8em;
  background-color: whitesmoke;  padding:2vw;}


        }


 @media (min-width: 48em) {
     .Sidebar {
      position: fixed;
      background:none;
      top: 3.56em;
      bottom: 0;
      left: 0;
      opacity: 100%;
      z-index: 2;
      width: 6em;
        }

.column {
  float: left;
}

.row {
  margin-left: 25vw;
  margin-top: .34em;
  margin-right: 2vw;
  margin-bottom: 2vw;
  align-content: center;
}

.row1 {
  margin-left: 25vw;
  margin-right: 2vw;
  height: 2em;
  align-content: center;}

.row2 {
  padding-top:.67em;
  padding-right: .67em;
  margin-left: 25vw;
  margin-right: 2vw;
  background-color:whitesmoke;}


.right {
 position: absolute;
  right: 2vw;
  width: 5em;
  height: 4em;
  background-color: none;}

.right1 {
  position: absolute;
  right: 2vw;
  width: 5em;
  height: 2em;
  }
  
hi {
  z-index:-2;
  background-color: yellow;
  position: absolute;
  right:0vw;
}

.middle {
  width: 34vw;
  height: 24vw;
  background-color: none;}

.middle1 {
  width: 33vw;
  height: 2em;
  background-color: none;
}

.left {
  width: 24vw;
  height: 24vw;
  margin-right:2vw;
  padding:0em;}

.left1 {
  width: 24vw;
  height: 2em;
  margin-right:2vw;}
  
h3 {
  margin-top:1.8em;
  margin-left:24.67vw;
  margin-right:2vw;
  background-color: whitesmoke;
  padding:.67vw;
  font-size:1.25em;
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
      z-index: 2;
      width: 6em;
      margin-left:7.34vw;}

.column {
  float: left;
  height: 2em;}

.row {
  margin-left: 25vw;
  margin-top: .34em;}

.row1 {
  margin-left: 25vw;
  margin-right: 2vw;
  height: calc(1em + 1.67vw);
  align-content: center;
  background-color: none;
  }

  .row2 {
  padding-top:.67em;
  padding-right: .67em;
  margin-left: 25vw;
  margin-right: 2vw;
  background-color:whitesmoke;}

.right {
 position: absolute;
 right: 2vw;
 width: 5em;
 height: 6vw;
 font-size: calc(.34em + 1vw);
 background-color: none;}

.right1 {
 position: absolute;
 right: 2vw;
 width: 5em;
 height: calc(1em + 1.34vw);
 font-size: calc(.34em + 1vw);}

hi {
  background-color: yellow;
  position: absolute;
  right:0vw;
}

.middle {
  width: 32vw;
  font-size: calc(.34em + 1vw);
  height: 24vw;}

.middle1 {
  width: 32vw;
  height: calc(1em + 1.34vw);
  font-size: calc(.34em + 1vw);
  background-color: none;
  
}

.left {
  width: 24vw;
  height: 24vw;
  margin-right:2vw;
  padding:0em;}

.left1 {
  width: 24vw;
  height: calc(1em + 1.34vw);
  margin-right:2vw;}

h3 {
  margin-top:1.3em;
  margin-left:23.95vw;
  margin-right:2vw;
  background-color: whitesmoke;
  padding:.67vw;
}
      }

@media (max-width: 33em) {
     .Sidebar {
      background:yellow;
      margin-left:-.0em;
      padding-left:.34em;
      padding-top: .5em;
      padding-bottom: .34em;
      padding-right: .34em;
      height: 12.67em;
      width: 7em;
      top:3.15em;
      z-index: 2;
        }
     
.column {
  float: left;
  height: 8em;
}

.row {
  width: 78vw;
  margin-left: 11vw;
  margin-right: 11vw;
  margin-bottom:2em;
  padding:0em;
  background-color:none;}

.row1 {
  width: 77vw;
  margin-left: 11vw;
  margin-right: 11vw;
  padding:0em;
  background-color: none;}

.row2 {
  margin-left: 2vw;
  margin-right:2vw;
  padding-top:.67em;
  padding-right: .67em;}

 .col-25 {
  text-align: right;
  color: black;
  font-size: 1.25em;
  font-weight: bold;
  background-color: whitesmoke;
  margin: 0em;
  padding:0em;}

.col-75 {
  text-align: right;
  color: black;
  margin: 0em;
  padding:0em;
  font-size: 1.25em;}

 hi {
    background-color:yellow;
    right:11vw;
}

.right {
  height: calc(.34em - 9vw);
  text-align: right;}

.right1 {
  text-align: right;
  background-color:none;
  height: 2em;
  position: absolute;
  right: 11vw;}

.middle {
  width: 42vw;
  margin-left:0em;
  padding-right:0em;
  padding-left:0em;}

.middle1 {
  width: 54vw;
  background-color:;
  text-align: left;
  height: 2em;
  position: absolute;
  left: 11vw;}

.left {
  width: 8vw;}

.left1 {
  width: 0vw;
  margin-right:0em;
  height: 3em;}        

h3 {
  font-size:1.25em;
  margin-top:4em;
  background-color: whitesmoke;
  padding:2vw;
  margin-top: 4.8em;}

        }
  
</style>