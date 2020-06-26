<template>
  <Layout>
  
  <div class="container">
  <div class="left">
    <div class="item item1">
      <h5 style="background-color:yellow; padding:.67em;line-height:1em;">Welcome to the Frequently asked questions page. Here are the answers to them. In the chance that you have a question that is not frequently asked, please <mark><g-link to="/contact">gimme a holler over here.</g-link><br></mark></h5>
</div>
      
</div><div class="right">
    <div class="item item4">
      <section id="accordion">
			  <div>
				<input type="checkbox" id="check-5"/>
				<label for="check-5" style="padding-bottom:0.67em;">Who are you?</label>
				<article>
					<p>I'm just a guy buying too many records. If not addiction, its gotta be defined as compulsion. My name is Evan Jordan. I'm an american guy, living in sweden. <br><br> I guess i've been collecting seriously for.. what year is it now? It's been almost 10 years now. I'd like to think i'm pretty knowledgable about all this stuff. Please drop me a line if you've got any questions, requests or just wanna chat. </p>
				</article>
			</div>
			<div>
				<input type="checkbox" id="check-1" />
				<label for="check-1" style="padding-bottom:0.67em;">What is this place all about?</label>
				<article>
					<p>Hope that this place becomes somewhere fun on the web. I'll be filing it with all sorts of records; the kind you like. All styles respected, but the stock is heavily weighted towards the lesser-known. It seems there is no end to the pool of '80s records. <br><br> In recent years, I'm leaning more and more towards do-it-yourself. Be it pop music, tropical, boogie, etc. so long as it hits right.</p>
				</article>
			</div>
      </section>
			</div>
    <div class="item item3" style="padding-bottom:0.67em;">
      <section id="accordion">
			<div>
				<input type="checkbox" id="check-8" />
				<label for="check-8" style="padding-bottom:0.67em;">What's with these prices?</label>
				<article>
					<p>Pricing is a good topic. Everything considered (rarity, hype, condition, and the music itself), the pricing also reflects the time spent chasing down these records. Also included in the price is the number of shitty records I've bought in the gambling process of "discovering" something unknown.<br><br>
          If the record is listed on discogs, I list cheaper. If there are no other copies available online, I'll try to find a price where it can sell for more in the future.<br><br>
          I agree there is a sizeable speculativity, but I want to err on being conservative in my pricing.</p>
				</article>
			</div>
		</section>
		</section>

        <section id="accordion">
			<div>
				<input type="checkbox" id="check-3" />
				<label for="check-3" style="padding-bottom:0.67em;">How do i pay?</label>
				<article>
					<p>Payments can be made either by Paypal or, in the case of Swedish residents, Swish.</p>
				</article>
			</div>
			<div>
				<input type="checkbox" id="check-4" />
				<label for="check-4">What can you tell me about shipping?</label>
				<article>
					<p>In your paypal payment, a tracking number will be added and can be searched <mark><g-link to="https://www.postnord.se/en/our-tools/track-and-trace2">right here.</g-link></mark>PostNord delivers within 5 working days in the EU and somewhere around 6-8 in North america and Asia.</p>
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
    padding-top: 0em;
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
    margin-top: 5.28em;
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

.right {
background-color: none;

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
    width: 78vw;
    margin-left: 23vw;
    background-color: none;
    margin-top: 1.67em;
    margin-left: 12em;
  }
  .left{
    width: 60%;
    margin-right: 1em;
    padding-top: 0em;
    }

  .right{
    width: 36%;
    margin-top: 2em;
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
    width: 64vw;
  }
  .left{
     width: 50%;
    margin-right: 1em;}
  
  .right{
    width: 46%;
    margin-right: em;
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
  font-size: 1.5em;
  line-height: 1em;
  background:none;
}
#accordion label:hover {
}

#accordion input:checked + label {
	background:none;
	font-size: 1.2
5em;
	margin-bottom: 0;
}
#accordion article {
	background:whitesmoke;
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
	height: auto;
	margin-bottom: .125em;
}

mark {
  background-color: orchid;
  color: black;
  }
</style>