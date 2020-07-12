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

<h3>In your paypal payment, a tracking number will be added and can be searched right here.PostNord delivers within 5 working days in the EU and somewhere around 6-8 in North america and Asia.</h3>
<div class="row">
  <div class="column left" style="background-color:#aaa;">
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
  </div>
</div>
<div class="row" style="margin-top:1.34em;">
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
  </div>
  </div>
</div>

<div class="row1" style="margin-top:1.34em;">
  <div class="column left1">
  </div>
  <div class="column middle1">
    <h5 style="margin-top:.5em;">Shipping (registered)</h5>
  </div>
  <div class="column right1">
    <h4 style="margin-top:.5em;">$120.00</h4>
  </div>
  </div>
</div>


<div class="row1" style="margin-top:1.34em; margin-bottom:9em;">
  <div class="column left1">
  </div>
  <div class="column middle1">
    <h5 style="margin-top:.34em;">Total</h5>
  </div>
  <div class="column right1" style="margin-bottom:3em;">
    <h4 style="margin-top:.34em;">$320.99</h4>
  </div>
  </div>
</div>


 <form action="/action_page.php">
  <div class="row2">
    <div class="col-25">
      <label for="name">Name</label>
    </div>
    <div class="col-75">
      <input type="text" id="fname" name="firstname" style="text-align:right; color:orchid;">
    </div>
  </div>
  <div class="row2">
    <div class="col-25">
      <label for="lname">Email address</label>
    </div>
    <div class="col-75">
      <input type="text" id="lname" name="lastname" style="text-align:right; color:orchid;" placeholder="">
    </div>
  </div>
  <div class="row2">
    <div class="col-25" style="text-align:right;" >
      <label for="topic">Topic</label>
    </div>
    <div class="col-75">
      <select id="topic" name="topic" style="color:black;">
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
      <textarea id="subject" name="subject" placeholder="" style="text-align:right; color:orchid; height:3em;" ></textarea>
    </div>
  </div>
   <div class="row2" style="margin-bottom:3em;">
    <div class="col-25" style="text-align:right; font-size:1.5em; margin-top:1em;" >
      <input type="submit" value="Checkout">
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

@media (max-width: 33em) {
  .container {
    padding-top: 0em;
    background: none;
    }
    .row2 {
  background-color:none;
  width: 100%;
}
 }

@media (max-width: 48em) {
  .container {
    margin-left:2vw;
    margin-right:2vw;
    margin-bottom:8em;
    margin-top: 4em;
    width: 95.67vw;
    }
  

.col-25 {
  text-align: right;
  color: black;
  font-size: 1.67em;
  }

.col-75 {
  text-align: right;
  color: black;
  }

.row2 {
  background-color: none;
  margin:0em;
}
}

@media (min-width: 48em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
    }
  
  .container{
    display: block;
    margin-left: 22vw;
    margin-top:2.34em;
    margin-right: 2em;
    margin-left: 12em;
    width: 73vw;
    }

  .col-25 {
  text-align: right;
  color: black;
  font-size: 1.67em;
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
    margin-left: 24.67vw;
    width: 62vw;
    }

  .col-25 {
  text-align: right;
  color: black;
  font-size: 1.5em;
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
  font-size: 1.5em;
  outline: none;
  background-color: none;
}

label {
  display: inline-block;
  outline: none;
}

input[type=submit] {
  background-color:white;
  font-size: 1.67em;
  font-family: 'tonii';
  border: none;

  padding:0em;
  cursor: pointer;
  float: right;
  outline: none;
}

input[type=submit]:hover {
  background-color:white;
  outline: none;
  padding:0em;
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
  height: calc(9em + 3vw);
  width: 69vw;
}
.row {
  margin-left: 2vw;
  align-content: center;
  padding-bottom:1.34em;
  
  opacity: 20%;}

.row1 {
  margin-left: 2vw;
  }

.row2 {
  padding-top: .67em;
  padding-right: .67em;
  margin-left: 18.34vw;
  align-content: center;
  padding-bottom:1.34em;
  width: 66vw;
  opacity: 60%;}

 .col-25 {
  text-align: right;
  color: black;
  margin: 0em;
  padding:0em;
  font-size: 1.25em;
  font-weight: bold;
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
  width: 12vw;
  background-color: violet;
  }

.right1 {
  width: 12vw;
  background-color:none;
  height: 3em;
  background-color: salmon;
  }

.middle {
  width: 41.34vw;
  margin-right:1.34vw;
  background-color: lime;}

.middle1 {
  width: 41.34vw;
  margin-right:1.34vw;
  margin-bottom:0em;
  background-color:red;
  height: 3em;
}
  
.left {
  width: calc(10em + 5vw);
  margin-right:2.34vw;}

.left1 {
  width: calc(10em + 5vw);
  height: 3em;
  margin-right:2.34vw;
  background-color: white;
} 

h3 {
  margin-top:4em;
  background-color: none;
  padding:2vw;
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
      z-index: 2;
      width: 6em;
        }

.column {
  float: left;
  background-color: skyblue;
}

.row {
  margin-left: 25vw;
  margin-top: .34em;
}

.right {
  width: 12vw;
  padding: 0em;
  position: absolute;

}
.middle {
  width: 32vw;
  margin-right:2.67vw;
}
.left {
  width: 24vw;
  height: 24vw;
  margin-right:2.67vw;
  padding:0em;
}
  
h3 {
  margin-top:1.3em;
  margin-left:25vw;
  margin-right:2vw;
  background-color: whitesmoke;
  padding:.67vw;
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
      margin-left:7.34vw;
        }
.column {
  float: left;
  height: 2em;
}
.row {
  margin-left: 24vw;
  margin-top: .34em;
}
.right {
  width: 12vw;
  padding: 0em;

}
.middle {
  width: 32vw;
  margin-right:1.67em;
}
.left {
  width: 21vw;
  height: 21vw;
  margin-right:1.67em;
  padding:0em;
}

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

.column1 {
  float: left;
  height: 8em;
  background-color: yellow;
}


.row {
  width: 24em;
  margin-left: 11vw;}

.row1 {
  width: 24em;
  margin-left: 11vw;
  padding:0em;}

.row2 {
  width: 24em;
  margin-left: 11vw;
  opacity: 100%;}

 .col-25 {
  text-align: right;
  color: black;
  margin: 0em;
  padding:0em;
  font-size: 1.25em;
  font-weight: bold;
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
  width: 3vw;
  text-align: right;
}

.right1 {
  width: 3vw;
  background-color:none;
  height: 3em;
  }

.middle {
  width: 53vw; 
}
.middle1 {
  width: 66vw;
  background-color:none;
  height: 3em;
  margin: 0em;
}


.left {
  width: 8vw;}

.left1 {
  width: 0vw;
  height: 3em;
}        


h3 {
  margin-top:4em;
  background-color: whitesmoke;
  padding:2vw;
}
        }
</style>