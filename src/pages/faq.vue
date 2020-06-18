<template>
  <Layout>
  
  <div class="container">
  <div class="left">
    <div class="item item1">
      <g-image style="margin-bottom:1em;" src="~/static/Images/b7.jpg"/>
       <p>UPN placed the series on hiatus on April 30, 2001, due to concerns about its low ratings; only two episodes had aired. Despite the network's claims, media commentators believed it would be removed from air following its poor performance.</p>
</div>
      
    
</div><div class="right">
  <div class="item item2"><section id="accordion">
			<div>
				<input type="checkbox" id="check-5" />
				<label for="check-5">Where do all these records come from?</label>
				<article>
					<p>While discussing the cancellation, McCouch felt it was "doomed to fail" from the beginning and referred to UPN as "a loser network at that time" due its treatment of the series. Cosgrove disagreed with McCouch's sentiment and believed the show's lack of success was not tied to the network specifically.</p>
				</article>
			</div>
			<div>
				<input type="checkbox" id="check-1" />
				<label for="check-1">What is this place all about?</label>
				<article>
					<p>Gillard developed the premise for All Souls from his belief that a medical facility would be an ideal setting for a horror series and his research on statistics of deaths that had taken place in a hospital.</p>
				</article>
			</div>
      </section>
			</div>
    <div class="item item3">
      <section id="accordion">
			<div>
				<input type="checkbox" id="check-8" />
				<label for="check-8">What's with these prices?</label>
				<article>
					<p>Reception of the series' pilot was mixed, with television critics divided over its structure.[5][9][25] Rob Owen of The Pittsburgh Post-Gazette gave the first episode a positive review, believing it set up enough story elements to show promise.</p>
				</article>
			</div>
		</section>
		</section>
  </div>
    
    <div class="item item4" style="margin-bottom:1em;">


    </div>
    
    <div class="item item6">
        <section id="accordion">
			<div>
				<input type="checkbox" id="check-3" />
				<label for="check-3">How do i pay?</label>
				<article>
					<p>A sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness.

Death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion..

Usually in a poignant but solemn manner.
Ballads are generally melodic enough to get the listener's attention but solemn manner. Ballads are generally melodic enough to get the listener's attention.</p>
				</article>
			</div>
			<div>
				<input type="checkbox" id="check-4" />
				<label for="check-4">How do i track an order?</label>
				<article>
					<p>The entire Sino-Indian border (including the western LAC, the small undisputed section in the centre, and the McMahon Line in the east) is 4,056 km (2,520 mi) long and traverses one Indian union territory, Ladakh, and four Indian states: Uttarakhand, Himachal Pradesh, Sikkim, and Arunachal Pradesh.[4] On the Chinese side, the line traverses the Tibet Autonomous Region. The term was first used by Chinese Premier Zhou Enlai in a 1959 note to Indian Prime Minister Jawaharlal Nehru.[2] The demarcation existed as the informal cease-fire line between India and China after the 1962 Sino-Indian War until 1993, when its existence was officially accepted as the 'Line of Actual Control' in a bilateral agreement.</p>
				</article>
			</div>
		</section>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  
  metaInfo: {
    
    title: 'Product'}
}
</script>


<style scoped>

table, td, th {
  border: 0px solid black;
  background-color:;
}

table {
  border-collapse: collapse;
  width: 100%;
}

td {
  width: 50%;
  vertical-align: top;
  background-color:none;
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
  padding-top: 0em;
  margin-left: 26vw;
  margin-bottom: 8em;
  background-color:none;
  }

.left {
  width: 100%;
}

.right{
  width: 37%;}

  .item1 {
  padding-bottom: 1.67em;
}

@media (max-width: 33em) {
  .container {
    margin-bottom:8em;
    padding-top: 3.67em;
    background: none;
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
    margin-left:4vw;
    margin-right:5vw;
    margin-bottom:8em;
    margin-top: 7.34em;
    width: 92vw;
    background-color:none;
    }
}

.item {
  margin-bottom: 0em;
  text-align: left;
  background:none;
  }

.item1 {
  padding-bottom: 1.67em;
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
    margin-left: 23vw;
    background-color: none;
    margin-top: 3.67em;
    margin-left: 12em;
  }
  .left{
    width: 60%;
    margin-right: 2em;
    max-width: 42vw;}

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
    background-color: none;
  } 
}
.item2 {
  margin-bottom: 1.5em;
}
.item3 {
  line-height: 1em;
  background-color: none;
}

.btn{
   font-size: 1.25em;
   line-height: 1.5em;
   cursor:pointer;
   display:inline-block;
   text-align: right;
   }

   #accordion input {
	display: none;
}
#accordion label {
	background:white;
	
	cursor: pointer;
	display: block;
	margin-bottom: .0;
	padding: .1725em 0em;
	z-index: 20;
  font-size: 1.25em;
  background:none;
}
#accordion label:hover {
}

#accordion input:checked + label {
	background:none;
	font-size: 1.25em;
	margin-bottom: 0;
}
#accordion article {
	background: lightgray;
	height:0px;
	overflow:hidden;
	z-index:10;
}
#accordion article p {
	padding: 1em;
}
#accordion input:checked article {
}
#accordion input:checked ~ article {
	border-bottom-left-radius: .25em;
	border-bottom-right-radius: .25em;
	height: auto;
	margin-bottom: .125em;
}
</style>