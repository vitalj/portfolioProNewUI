<template>
  <div class="home">
  <div class="hello">
   <h1 id="title">VITAL Jérémy</h1>
   <h2 id="subtitle"><p>Développeur Junior </p></h2>
    <h3>
      <p>Curieux ⎮ Travailleur ⎮ Passionné<p/>
      <p >À la recherche d'un emploi à Lyon.</p>
    </h3>

  	<div class="icons-social">
			<a target="_blank" href="https://github.com/vitalj"><i class="fab fa-github"></i></a>
			<a target="_blank" href="https://www.linkedin.com/in/jeremy-vital-dev/"><i class="fab fa-linkedin"></i></a>
       <a href="mailto:jeremy.vital@gmail.com"><i class="fas fa-envelope"></i></a>

  </div>

    </div>
  </div>
</template>

<style scoped>

#title {
  font-size: 6rem;
}

#subtitle {
  font-size: 5rem;
}

h3 {
  font-size: 3rem;
}

.home {
  height: 100vh;
  display: flex; /* contexte sur le parent */
  flex-direction: column; /* direction d'affichage verticale */
  justify-content: center; 
}

.icons-social {
	font-size: 5rem;
 display: flex;
 justify-content: space-evenly;
}

.icons-social i {
  color: white;
}
.icons-social i:hover {
  color: black;
}
.hello {
  padding: 0;
  width: 90vh;
  margin-left: auto;
  margin-right: auto;
}

</style>
