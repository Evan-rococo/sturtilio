
<template>

  <Layout>
  <input type="range" min="150" max="400" value="300"> 
<div>
<img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg'%3E%3Ccircle cx='150' cy='150' r='135' stroke='%23003300' stroke%2Dwidth='4' fill='%236ab150'/%3E%3C/svg%3E"  alt="test shape-outside + SVG">

<p>En un lugar de la Mancha, de cuyo nombre no quiero acordarme, no ha mucho tiempo que vivía un hidalgo de los de lanza en astillero, adarga antigua, rocín flaco y galgo corredor. Una olla de algo más vaca que carnero, salpicón las más noches, duelos y quebrantos los sábados, lentejas los viernes, algún palomino de añadidura los domingos, consumían las tres partes de su hacienda. El resto della concluían sayo de velarte, calzas de velludo para las fiestas con sus pantuflos de lo mismo, los días de entre semana se honraba con su vellori de lo más fino. Tenía en su casa una ama que pasaba de los cuarenta, y una sobrina que no llegaba a los veinte, y un mozo de campo y plaza, que así ensillaba el rocín como tomaba la podadera. Frisaba la edad de nuestro hidalgo con los cincuenta años, era de complexión recia, seco de carnes, enjuto de rostro; gran madrugador y amigo de la caza. </p>
</div>
<simple-component></simple-component>


  </Layout>
</template>

<script>

Vue.component('simple-component',{
    template: '<h2>Simpo Component</h2>'
})
    
</script>


<style scoped>

  div{width:40em;
  margin:1em auto;
  padding:1em;
  border:1px solid #d9d9d9;
  font-family:Verdana, Geneva, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;  
}
img{
  width:300px;
  height:300px;
  float:left;
  shape-margin:.5em;
  /*shape-outside:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg'%3E%3Ccircle cx='150' cy='150' r='135' stroke='%23003300' stroke%2Dwidth='4' fill='%236ab150'/%3E%3C/svg%3E");*/
}
input{ width:40em; margin: 2em auto; display:block;}


.container {
  display: flex;
  flex-direction: column;
  padding-top: 3.67em;
  margin-left: 26vw;
  margin-right: 2em;
  margin-bottom: 8em;
  background-color:none;
  }

.left {
  width: 100%;
  }

.right{
  width: 37%;
  }

@media (max-width: 33em) {
  .container {
    margin-bottom:8em;
    padding-top: 3.67em;
    background:none;
    }

  .item3{
    font-size: 1em;
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
    margin-left:5vw;
    margin-right:5em;
    margin-bottom:8em;
    margin-top: 3.67em;
    width: 90vw;
    background-color:none;
    }
  }

.item {
  margin-bottom: 0em;
  text-align: left;
  background:none;
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
    margin-left: 22vw;
    background-color: none;
    margin-right: 2em;
    margin-left: 12em;
    }

  .left{
    width: 56%;
    margin-right: 2em;
    max-width: 42vw;
    }

  .item1 {
    opacity: 100%;
    }
    
  .item3 {
    background-color: none;
    text-decoration: none;
    }

  .right{
    width: 36%;
    background-color: none;
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
    }

  .left{
    width: 63%;
    margin-right: 2em;
    max-width: 36vw;
    }

  .item1 {
    opacity: 100%;
    }

  .item3 {
    background-color: none;
    text-decoration: none;
    }

  .right{
    width: 33%;
    background-color: none;
    } 
  }


mark {
  background-color: yellow;
  color: black;
  }


     .Sidebar1 {
      background:orange;
      padding:.67em;
      
        }
      

 .Sidebar1 {
    transform: translate3d(-200%, 0, 0);
    top: 3em;
    
  }
 
  .Sidebar1.open {
    transform: translate3d(0, 0, 0);
     .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  }
</style>