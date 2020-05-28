<template>
  <Layout>
      <div class="sidenav" style="margin-top:3.79em; margin-left:1em;">
  <g-link to="/genre1/">new stuff</g-link>
  <g-link to="/genre1/">afro</g-link>
  <g-link to="/genre1/">boogie</g-link>
  <g-link to="/genre1/">esoteric</g-link>
  <g-link to="/genre1/">pop music</g-link>
  	<div class="collection-sort" style="margin-top:2em">
				<label><h1>Sort by</h1></label>
				<select>
		      <option value="/">price</option>
		      <option value="/">date</option>
		      <option value="/">sale</option>
		    </select>
			</div>
		</div>
  </div>
    <nav class="product-filter" style="margin-left:35em;">
	</nav>
	
	<section class="products" style= "margin-left:12em; margin-top: 2.5em;">
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/hrb2.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Stand up for your rights LP</h3>
				<h3>Feel it</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
			 <g-link to="/product/">
    <g-image src="~/static/Images/hrb6.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Walk in the park 12"</h3>
				<h3>Eros</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/hrb3.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Light tanning LP</h3>
				<h3>Sun tan club</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
			 <g-link to="/product/">
    <g-image src="~/static/Images/hrb12.jpg" width="450em;"/>
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
    <g-image src="~/static/Images/hrb7.jpg" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Coco rico LP</h3>
				<h3>Cool aid</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/hrb9.jpg" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Bohobe spirits music LP</h3>
				<h3>Norberto de noah</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/hrb11.jpg" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Magmama 12"</h3>
				<h3>Stimela</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/hrb10.jpg" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Fight for your rights LP</h3>
				<h3>Feel it</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/hrb8.jpg" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Sick sick sick EP</h3>
				<h3>Sex total</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/hrb4.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>Tennesse stud 12"</h3>
				<h3>Never was a horse like a</h3>
			</div>
		</div>
		
	</section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'New stuff'
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

/*------------------------------------*\
    $MAIN
\*------------------------------------*/

@font-face {
    font-family: 'Elmo';
    src: url('../static/elmer-webfont.woff') format('woff'), /* Modern Browsers */
         url('../static/elmer-webfont.ttf') format('truetype'); /* Safari, Android, iOS */
             font-style: normal;
    font-weight: normal;
    text-rendering: optimizeLegibility;}

/* Typography */

h1 {
  font-family: "elmo";
  font-size:  1.5em;
}

h3 {
  font-family: "elmo";
  font-size: 1em;
  line-height: 1em;
}

/* Product Layout */

.product-filter {
	display: flex;
	padding: 0px 0;
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
	padding-right: 20px;
}

label {
	color: black;
  font-family: "elmo";
	font-size: 1em;
	font-weight: 500;
	line-height: 2em;
}

.products {
	display: flex;
	flex-wrap: wrap;
}

.product-card {
	display: flex;
	flex-direction: column;
	padding: 1em;
	flex: 1 48%;
	
	background-color: none;
}

.product-image img {
	width: 100%;
}

.product-info {
	margin-top: auto;
	padding-top: .67em;
	text-align: right;
}

@media ( max-width: 750px ) {
	
	.product-card {
		flex: 1 100%;
	}
	
	.products .product-card:first-child, 
	.products .product-card:nth-child(2) {
		flex: 2 50%;
	}
	
}

@media ( max-width: 600px ) {
	
	.product-card {
		flex: 1 100%;
	}
	
}

@media ( max-width: 600px ) {
	
	h1 {
		margin-bottom: 0;
	}
	
	.product-filter {
		flex-direction: column;
	}
	
	.sort {
		align-self: flex-start;
	}
	
}


.main {
  margin-top: 30px; /* Add a top margin to avoid content overlay */
}

.sidenav {
  width: 9em;
  position: fixed;
  z-index: 1;
  background: none;
  overflow-x: hidden;
  color: black;
  margin-right: 333px
}

.sidenav a {
  text-decoration: none;
  font-size: 1.5em;
  line-height: 1em;
  display: block;
}

.sidenav a:hover {
  color: red;
}

.main {
  margin-left: 140px; /* Same width as the sidebar + left position in px */
  font-size: 2em;
}





















</style>