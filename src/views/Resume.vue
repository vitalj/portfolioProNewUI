<template>
  <div class="about">
    <h1>En savoir plus à propros de moi :</h1>
      <p id="my-txt">J'ai fait ma formation de développeur logiciel à l'Access Code School et suis titulaire du diplôme de développeur logiciel (titre de niveau III). Je cherche un emploi de développeur junior à Lyon, alors si vous êtes intéressé n'hésitez pas à me contacter !
</p>
      
    <div class="cv"></div>
    <div><div>
    <img src="../assets/CV.jpg" id="img" alt="CV de Jérémy VITAL" />
  </div>

    <!-- <a target="_blank" href="https://vitalj.github.io/pdf/CV-Jeremy-Vital.pdf">   <i class="fas fa-download"></i> -->
        <a target="_blank" href="https://vitalj.github.io/pdf/CV-Jeremy-Vital.pdf">  <i class="fas fa-folder-open"></i>
</a>
  </div>
</div>

</template>
<style scoped>

#my-txt {
    margin: 0 auto;
    width: 50vw;
    padding-bottom: 2vh;
    Font-Family: 'Roboto Slab', Serif;
    Font-Size: 0.875rem;
  }



.fas {
  font-size: 1.8rem; 
   color: white;
  background-color: rgba(0, 0, 0, 0);
   border: 1px solid rgba(247, 212, 212, 0);
   padding-top: 2vh;
}

.far:hover {
  color: black;
}


img .card {
  background-color: rgba(180, 179, 179, 0);
  border-radius: 0.25rem;
  box-shadow: 0 20px 40px -14px rgba(0, 0, 0, 0.25);
  display: flex;
  flex-direction: column;
  overflow: hidden;
  border: 1px solid rgb(36, 36, 36);
}

  .about {
    padding-top: 5vh;
  }

#img {
  height: 81vh;
}
</style>