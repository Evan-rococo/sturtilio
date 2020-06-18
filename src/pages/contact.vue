<template>
  <Layout>
  
  <div class="container" style="background-color:lightgrey; padding-bottom:2em; padding-right:.67em; padding-top:.67em; padding-left:.67em;">
  <form action="/action_page.php">
  <div class="row">
    <div class="col-25" >
      <label for="name">Name</label>
    </div>
    <div class="col-75">
      <input type="text" id="fname" name="firstname" style="text-align:right; color:red;" placeholder="">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="lname">Email address</label>
    </div>
    <div class="col-75">
      <input type="text" id="lname" name="lastname" style="text-align:right; color:red;" placeholder="">
    </div>
  </div>
  <div class="row">
    <div class="col-25" style="text-align:right;" >
      <label for="topic">Topic</label>
    </div>
    <div class="col-75">
      <select id="topic" name="topic" style="color:red;">
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
      <textarea id="subject" name="subject" placeholder="" style="text-align:right; color:red; height:9em;" ></textarea>
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
  padding-top: 3.67em;
  margin-left: 26vw;
  margin-right: 0em;
  margin-bottom: 8em;
  background-color:none;
  width: 50vw;
  }

@media (max-width: 48em) {
  .container {
    margin-left:5vw;
    margin-right:5vw;
    margin-bottom:0em;
    padding-top:0em;
    margin-top:7.25em;
    width: 90vw;
    background-color:none;
    }
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

   
@media (min-width: 48em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
    }
  
  .container{
    display: block;
    margin-left: 22vw;
    background-color: none;
    padding-top:0em;
    margin-top:3.67em;
    margin-right: 2em;
    margin-left: 12em;
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
  padding-bottom: 1em;
  border: 0px;
  resize: vertical;
  font-family: 'elmo';
  font-size: 1.25em;
  outline: none;
  background-color: lightgrey;
}

label {
  display: inline-block;
  outline: none;
}

input[type=submit] {
  background-color: lightgray;
  font-size: 1.5em;
  font-family: 'elmo';
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


</style>