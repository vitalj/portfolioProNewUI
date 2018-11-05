<template>
<div>
      <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css">
<link href="https://fonts.googleapis.com/css?family=Roboto+Slab|Ruda" rel="stylesheet">
        <div class="navbar">
      <ul>
        <li>
          <router-link to="/">Accueil</router-link>
        </li>
        <li>
          <router-link to="/resume">Mon CV</router-link>
        </li>
        <li>
          <router-link to="/projects">Mes projets</router-link>
        </li>
      </ul>
    </div>
    <router-view />

  </div>
</template>
<style>

.hello {
  padding-top: 5vh;
}
h1 {
Font-Family: 'Ruda', Sans-Serif;
Font-Size: 2.5rem;
}

h2 {
  Font-Family: 'Ruda', Sans-Serif;
  Font-Size: 2rem;
}

body {
  margin-top:0;
  margin-bottom: 0;
  background: -webkit-linear-gradient(70deg, #ff6464 30%, #5ac8fa 80%);
  background: -o-linear-gradient(70deg, #ff6464 30%, #5ac8fa 80%);
  background: -moz-linear-gradient(70deg, #ff6464 30%, #5ac8fa 80%);
  background: linear-gradient(70deg, #ff6464 30%, #5ac8fa 80%);  
  text-align: center;
  Font-Size: 15px; 
  position: relative;
  color: white;
}

.navbar {
  background: black;
  height: 5vh;
  position: fixed;
  overflow: hidden;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1;
  -webkit-transition: .13s all;
  transition: .13s all;
    box-sizing: border-box;
  margin: 0;
  padding: 0;
  Font-Family: 'Roboto', Sans-Serif;

}

.navbar ul {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 95vw;
  box-sizing: border-box;
  overflow: hidden;
  margin: 0;
  padding: 0;
}

.navbar ul li {
  list-style: none;
}


.navbar li:first-child {
  margin-right: auto;
  /* font-size: 2em; */
  font-weight: bold;
}

.navbar a {
  text-decoration: none;
    font-size: 1.2rem;
  padding: 12px;
   color: white;
   -webkit-transition: .3s all;
  transition: .3s all;

}

.navbar a:hover {
  color: grey;
}




</style>
<script>

</script>