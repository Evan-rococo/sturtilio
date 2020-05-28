<template>
  <Layout>
        <div class="sidenav">
  <g-link to="/genre1/">new stuff</g-link>
  <g-link to="/genre1/">afro</g-link>
  <g-link to="/genre1/">boogie</g-link>
  <g-link to="/genre1/">esoteric</g-link>
  <g-link to="/genre1/">pop music</g-link>
  </div>
<div class="content" style= "margin-top:5em; margin-left:12em;"></div>
<div class="flex_container" style= "margin-top:5em; margin-left:12em;">
  <div class="flex_item_left">
    <g-link to="/product/">
    <g-image src="~/static/Images/hrb11.jpg" width="450em;"/>
    </g-link>
      <div class="p" style= "text-align:right;">Last updated 05.29</div>
  </div>
  <div class="flex_item_right">
       <p>pA sentimental ballad is an emotional <mark>milk</mark> style of music that often deals with <mark>romantic and intimate relationships, and to a lesser extent, war (protest songs)</mark>, loneliness, death, drug abuse, politics and religion, usually in a poignant but solemn manner.[1] Ballads are generally melodic enough to get the listener's attention.[2]</p>

  </div>
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

<style>
.home-links a {
  margin-right: 1rem;
}

/* Main content */
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

.flex_container {
  display: flex;
  width: 100%;
}
.flex_item_left {
  width: 400px;
  background: none;
}
.flex_item_right {
  flex: 1;
  background: none;
}
mark {
  background-color: yellow;
  color: black;
}


body{
  background: none;
  font-family: 'elmo';
}

.search {
  width: 100%;
  position: relative;
  font-family: "Elmo";
  font-size: 1em;
  display: flex;
  border: 0;
  color: black;
  border-color: transparent;
  float: none;
}

.searchTerm {
  width: 100%;
  font-family: "Elmo";
  font-size: 1em;
  text-decoration-color: black;
  background: none;
  border: 0;
  border-color: transparent;
  text-align: left;
  padding:0px;
  height: 46px;
}

.searchTerm:focus{
  text-decoration-color: black;
  font-family: "Elmo";
  font-size: 1em;
  border: 0;
  border-color: transparent;
  outline: none;
  background:none;
  text-align: left;
  padding:0px;
  height: 46px;
}

.searchButton {
  width: 1em;
  height: 1em;
  background:none;
  text-align: center;
  cursor: pointer;
  font-size: 1.5em;
  border: 0;
  border-color: transparent;
  outline: none;
  padding:16px;
}

/*Resize the wrap to see the search bar change!*/
.wrap{
  width: -49%;
  float: none;
  position: absolute;
  top: -17%;
  left: 42%;
  transform: translate(-60%,-20%);
  border-color: transparent;
  outline: none;
}
</style>
