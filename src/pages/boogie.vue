<template>
<body>
	  <div class="overlay"></div>
    <div class="modal" style="transform: rotate(-9deg); mix-blend-mode: normal;"><g-image src="~/static/d64.png"/></div>
  <Layout>
	     <div class="Sidebar" v-bind:class="{ open: isActive}" style="opacity:100%;">
        <g-link to="/newstuff">New stuff</g-link><br>
            <g-link to="/afro">afro</g-link><br>
            <mark style="padding:.1725em; mix-blend-mode: darken;"><g-link>boogie</g-link></mark><br>
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
    <nav class="product-filter">
	</nav>
	<section class="products">
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/p1.png" width="450em;" height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p>"Ich träume so leise von dir" LP</p>
				<p>Becker, Stegmann, Lasker-Schuler</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
			 <g-link to="/product/">
    <g-image src="~/static/Images/p2.png" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p>Mr. mac 12"</p>
				<p>Steve williams</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/p3.png" width=450em; height="450em;"/>
    </g-link>
			</div>
	<div class="product-info">
				<p>Sketches of anderland 7"</p>
				<p>Angelo vanotti</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/p4.png" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>"I know you feel it" LP</h3>
				<h3>Kumasi</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/p5.png" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>S/t LP</h3>
				<h3>Puzzle</h3>
			</div>
		</div>

		<div class="product-card">
			<div class="product-image">
			 <g-link to="/product/">
    <g-image src="~/static/Images/w6.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Broken ally 7"</h3>
				<h3>Eddy alimante</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/p2.png" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Tender lover 7"</h3>
				<h3>Eddy amiante</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/p3.png" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>My name is bond 12"</h3>
				<h3>Beat control</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/p1.png" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Feeling Nice 12"</h3>
				<h3>Jam-master king</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/p4.png" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>"Jazz maiden" EP</h3>
				<h3>Accura</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/p3.png" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>"Böhöbé Spirits Music" LP</h3>
				<h3>Norberto de nöah</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/g1.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Tennesse stud 12"</h3>
				<h3>Never was a horse like a</h3>
			</div>
		</div>
		
	</section>
	
  </Layout></body>
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

html,body,div,span,applet,object,iframe,
h1,h2,h3,h4,h5,h6,p,blockquote,pre,
a,abbr,acronym,address,big,cite,code,
del,dfn,em,img,ins,kbd,q,s,samp,
small,strike,strong,sub,sup,tt,var,
b,u,i,center,
dl,dt,dd,ol,ul,li,
fieldset,form,label,legend,
table,caption,tbody,tfoot,thead,tr,th,td,
article,aside,canvas,details,figcaption,figure,
footer,header,hgroup,menu,nav,section,summary,
time,mark,audio,video{
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    font:inherit;
    vertical-align:baseline;
}
/* HTML5 display-role reset for older browsers */
article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section{
    display:block;
}
body{
    line-height:1;
}
ol,ul{
    list-style:none;
}
blockquote,q{
    quotes:none;
}
blockquote:before,blockquote:after,
q:before,q:after{
    content:’’;
    content:none;
}

ins{
    text-decoration:none;
}
del{
    text-decoration:line-through;
}

table{
    border-collapse:collapse;
    border-spacing:0;
}

/* Product Layout */

.product-filter {
	display: flex;
	}

.sort {
	display: flex;
	align-self: flex-end;
	}

.collection-sort {
 	display: flex;
 	flex-direction: column;
 	}

.collection-sort:first-child {
	padding-right: 0px;
}

label {
	color: orange;
}

.products {
	display: flex;
	flex-wrap: wrap;
	margin-top:6em;
	margin-left:1vw;
	margin-bottom: 8em;
	width:98vw;
	background-color:none;
	
}

.product-card {
	display: flex;
	flex-direction: column;
	flex: 1 30%;
	padding-left: 1vw;
	padding-right: 1vw;
}

.product-image img {
	width: 100%;
}

.product-info {
	margin-top: auto;
	padding-top: .67em;
	padding-bottom: 1em;
	text-align: right;
	font-size: calc(.34em + 1.34vw);
}

@media ( max-width: 48em ) {
	
	.product-card {
	flex: 1 46%;
	}
	
	.products .product-card:first-child, 
	.products .product-card:nth-child(2) {
	flex: 2 30%;
	}

	.overlay {
        position: absolute;
        top: 0;
        left: 0;
        height: 1%;
        width: 1%;
        z-index: 10;
      }

    .modal {
        width: 28vw;
        position: fixed;
        top: 30%;
        left: 36%;
        text-align: center;
        z-index: 11;
      }

	.header a {
    float: right;
    display: block;
    align-items: center;
    background-color:none;
    margin-right: .5em;
    margin-top:0em;
    }

    .header {
    float: right;
    display: block;
    position: fixed;
    left: 0;
    top: 0;
    }
    
    .header-right {
    margin-top:0.96em;
    font-size: 1.5em;
    position: relative;
    left: 0;
    top: 0;
    background-color:none;
  	}

}

@media ( max-width: 33em ) {
	

}

@media ( min-width: 48em ) {
	
	h1 {
		margin-bottom: 0;
	}

	.products {
	display: flex;
	flex-wrap: wrap;
	margin-top: 2.34em;
	margin-left:23.67vw;
	width:75.34vw;
	flex: 1 36%;
  background-color: none;
	}

	.product-info {
	margin-top: auto;
	padding-top: .67em;
	padding-bottom: 1em;
	text-align: right;
	font-size: calc(.34em + .67vw);
}
	
	.product-filter {
		flex-direction: column;
	}
	
	.sort {
		align-self: flex-start;
	}

	 .overlay {
        position: absolute;
        top: 0;
        left: 0;
        height: 1%;
        width: 1%;
        z-index: 10;
      }
      .modal {
        width: 24.34vw;
        position: fixed;
        top: 30%;
        left: 49.2%;
        text-align: center;
        z-index: 11;
      }

	    .form.example input[type=text] {
  font-family: 'elmo';
  font-size: 1em;
  float: left;
  width: 90%;
  border: none;
  outline: 0px solid transparent;
  padding-left:0em;
  background: none;
  text-decoration: black;
}




.header-right {
  float: right;
  font-size: 2em;
  margin-right: 9vw;
  background-color: none;
  }}

@media screen and (max-width: 64em) {

  .header a {
    background-color: none;
    margin-left: .86vw;
    float: left;
    }

   .header {
    background-color:none;
    } 
    
  .header-right {
    float: fixed;
    background-color: none;
  }
}

  
@media screen and (max-width: 33em) {
	.product-card {
		flex: 2 50%;
	}

	.products {
	display: flex;
	flex-wrap: wrap;
	margin-top: 6em;
	margin-left: 1vw;
	width:98vw;
	flex: 1 36%;
  background-color:none;
	}	

  .header a {
  float: right;
  display: block;
  text-align: right;
  margin-right: 1.67vw;
  position: relative;
  left: 0;
  top: 0;
  }

 .header {
  position: fixed;
  left: 0;
  top: 0;
} 
    
.header-right {
  float: left;
  margin-left:3em;
  margin-top:-1.5em;
  position: fixed;
  left: 0;
  top: 0;
  }
}

form.example input[type=text] {
  font-family: 'elmo';
  font-size: 1.67em;
  float: left;
  width: 100%;
  padding-left:0em;
  background: none;
  text-decoration: black;
}

form.example button {
  float: left;
  width: 10%;
  padding: 0px;
  color: none;
  border: none;
  cursor: pointer;
  margin-left:0em;
  outline: 0px solid transparent;
}

form.example button:hover {
  background: red;
  border: none;
}

form.example::after {
  content: "";
  clear: both;
  display: table;
  font-family: 'elmo';
  text-decoration: black;
  
}

/* Change background on mouse-over */
.navbar a:hover {
  color: red;
}
/* Main content */
.main {
  margin-top: 0px;}
.Sidebar {
  background:none; opacity: 100%;
  position: fixed;
  bottom: 0;
  left: 0;
  z-index: 0;
  margin-left: 8vw;
  font-size: 1.67em;
  width: 7em;
}
.Hamburger {
  position: fixed;
  margin-top: 3em;
  opacity: 0;
  z-index: 2;
  margin-left:2.5vw;
}
@media (max-width: 48em) {

  .header a {
  float: right;
  display: block;
  text-align: right;
  margin-right: 1.67vw;
  position: relative;
  left: 0;
  top: 0;
  }
  .Sidebar {
    transform: translate3d(-100%, 0, 0);
    top: 3em;
    
  }
  .Hamburger {
    opacity: 1;
    margin-left:2.5vw;
    top: -2.2em;
  }
 
  .Sidebar.open {
    transform: translate3d(0, 0, 0);
     .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  
  .topnav a, .topnav input[type=text] {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 1.2em;
        }
      }
    }

    form.example input[type=text] {
  font-family: 'elmo';
  font-size: 1em;
  float: left;
  width: 100%;
  border: none;
  outline: 0px solid transparent;
  padding-left:0em;
  background:none;
  text-decoration: black;
}


@media (max-width: 64em) {
  .Sidebar {
  position: fixed;
  background:none;
  top: 3.6em;
  bottom: 0;
  left: 0;
  background:none;
  opacity: 100%;
  z-index: 0;
  margin-left: 2.34vw;
  width: 6em;
  }
}

.topnav input[type=text] {
  float: right;
  border: none;
  margin-top: 1em;
  margin-right: 1.8em;
  margin-left: 3vw;
  position: relative;
}

.sticky {
  position: relative;
  top: 0;
  width: 100%;}

  
   @media (max-width: 48em) {
     .Hamburger {
  margin-left: 2.34vw;
}
     
      .Sidebar {
      background:yellow;
      margin-left:-.0em;
      padding-left:.34em;
      padding-top: .5em;
      padding-bottom: .34em;
      padding-right: .34em;
      height: 12.67em;
      width: 7em;
        }
      }
 @media (min-width: 64em) {
    	.products {
	margin-top: 2.6em;
  background-color: none;
	}	
     .Sidebar {
      position: fixed;
  background:none;
  top: 3.6em;
  bottom: 0;
  left: 0;
  background:none;
  opacity: 100%;
  z-index: 0;
  margin-left: 7.34vw;
  width: 6em;
        }
      }
  #nav{
  display:none;
}
</style>