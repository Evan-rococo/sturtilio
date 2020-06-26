
<template>
  <Layout>
    <nav class="product-filter">
	</nav>
	<section class="products">
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/b10.jpg" width="450em;" height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p>"Stand up for your rights" LP</p>
				<p>Feel it</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
			 <g-link to="/product/">
    <g-image src="~/static/Images/s4.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p>Walk in the park 12"</p>
				<p>Eros</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/b19.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
	<div class="product-info">
				<p>Walk in the park 12"</p>
				<p>Eros</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/s1.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>"Light tanning" LP</h3>
				<h3>Sun tan club</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/hrb18.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>"Sex total" EP</h3>
				<h3>Various artists</h3>
			</div>
		</div>

		<div class="product-card">
			<div class="product-image">
			 <g-link to="/product/">
    <g-image src="~/static/Images/b14.jpg" width=450em; height="450em;"/>
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
				<h3>"Coco rico" LP</h3>
				<h3>Cool aid</h3>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="~/static/Images/hrb20.jpg" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>"Bohobe spirits music" LP</h3>
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
    <g-image src="~/static/Images/hrb16.jpg" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<h3>"Fight for your rights" LP</h3>
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
				<h3>"Sick sicc" EP</h3>
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
    title: 'Genre'
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
	margin-top:3.67em;
	margin-left:26vw;
	margin-bottom: 8em;
	width:66vw;
	background-color:none;
	
}

.product-card {
	display: flex;
	flex-direction: column;
	flex: 1 30%;
	padding-left:.5em;
	padding-right:.5em;
}

.product-image img {
	width: 100%;
}

.product-info {
	margin-top: auto;
	padding-top: .33vw;
	padding-bottom: .67em;
	text-align: right;
}

@media ( max-width: 48em ) {
	
	.product-card {
	flex: 1 46%;
	}
	
	.products .product-card:first-child, 
	.products .product-card:nth-child(2) {
	flex: 2 30%;
	}

	.products {
	display: flex;
	flex-wrap: wrap;
	margin-top: 7.3em;
	margin-left:1.67vw;
	margin-right:2vw;
	margin-bottom:8em;
	width:96vw;
	background-color:none;
	}
}

@media ( max-width: 33em ) {
	
	.product-card {
		flex: 2 50%;
	}

	.products {
	display: flex;
	flex-wrap: wrap;
	margin-top: 7.34em;
	margin-left:1em;
	width:94vw;
	flex: 1 36%;
	}
	
}

@media ( max-width: 1300px ) {
	
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

</style>