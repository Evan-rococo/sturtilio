<template>
  <Layout>
  
  <div class="container">
    
    <h5 style="background-color:yellow; padding:.67em;line-height:1em;">UPN placed the series on hiatus on April 30, 2001, due to concerns about its low ratings; only two episodes had aired. Despite the network's claims, media commentators believed it would be removed from air following its poor performance. <br>
    <br>How do you reference an image in your src/assets/images folder in your style in your vue component?</h5>
  <form action="/action_page.php">
  <div class="row">
    <div class="col-25" >
      <label for="name">Name</label>
    </div>
    <div class="col-75">
      <input type="text" id="fname" name="firstname" style="text-align:right; color:orchid;" placeholder="">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="lname">Email address</label>
    </div>
    <div class="col-75">
      <input type="text" id="lname" name="lastname" style="text-align:right; color:orchid;" placeholder="">
    </div>
  </div>
  <div class="row">
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
  <div class="row">
    <div class="col-25">
      <label for="subject">Subject</label>
    </div>
    <div class="col-75">
      <textarea id="subject" name="subject" placeholder="" style="text-align:right; color:orchid; height:9em;" ></textarea>
    </div>
  </div>
  <div class="row">
    <input type="submit" value="Submit">
  </div>
  </form>
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
  margin-top: 1.67em;
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
 }

@media (max-width: 48em) {
  .container {
    margin-left:5vw;
    margin-right:5vw;
    margin-bottom:8em;
    margin-top: 5.2em;
    width: 90vw;
    }
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
    margin-left: 27vw;
    margin-right: 2em;
    margin-top:4em;
    width: 64vw;
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
  font-family: 'elmo';
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

</style>